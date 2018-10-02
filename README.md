# wine-test

See `./docs/challange.pdf`

## Requirements

- Python 3
- Virtualenv

## Install

In a terminal, run the following to create the Python virtualenv and install the dependencies for the project:

```py
virtualenv -p python3 .env && . .env/bin/activate
pip install -r requirements.txt
```

## Run

Run the following command to open the Jupyte Notebook for the project:

```py
jupyter notebook notebook.ipynb
```

## Data

The dataset used in this project is included as `data.csv`. This dataset has the following attributes:

- `type`
- `fixed acidity`
- `volatile acidity`
- `citric acid`
- `residual sugar`
- `chlorides`
- `free sulfur dioxide`
- `total sulfur dioxide`
- `density`
- `pH`
- `sulphates`
- `alcohol`
- `quality`
