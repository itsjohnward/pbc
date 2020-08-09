<p align="center"><img width=150px src="./pbc-logo.png"></p>
<h1 align="center">Price Band Classification Modeling</h1>
<p align="center"><img src="https://img.shields.io/badge/python-v3.8-blue.svg"></p>

## Installation & Usage

1. `git clone git@github.com:itsjohnward/pbc.git` and navigate into the directory
2. [Install pipenv](https://pipenv-fork.readthedocs.io/en/latest/install.html#installing-pipenv)
3. `pipenv install` to install all the requirements
4. Set your POLYGON_API_KEY environment variable, e.g. `export POLYGON_API_KEY=YOURKEY`. To get an API key, you must have a Polygon account. Sign up or log in [here](https://polygon.io/signup?next=/dashboard/billing/plan) to retrieve your key.
5. `pipenv run jupyter notebook`
6. Execute the [pbc-analysis.ipynb](./pbc-analysis.ipynb) notebook. If you don't have a local copy of the data saved, it will download all the data you need from Polygon.