# Machine Learning for Data Analysis

This repository contains Jupyter notebooks developed for the **Machine Learning for Data Analysis** course during Applied Mathematics Master’s program.

<i>The full course description prepared by the <a href="https://pwr.edu.pl/en/">university</a> can be found here: <a href="./about.pdf">about.pdf</a></i>

## Project structure

- `datasets/`, datasets used in the analyses (for example `house_prices.csv`)
- `notebooks/`, jupyter notebooks with solutions and experiments (for example `solutions1.ipynb`)
- `requirements.txt`, list of Python dependencies required to run the notebooks

## Environment setup (pyenv)

Below is an example of how to configure the environment using `pyenv` and a virtual environment:

```bash
# install a chosen Python version (e.g. 3.11.x)
pyenv install 3.13.2

# create a virtual environment for this project
pyenv virtualenv 3.13.2 ml

# associate the virtual environment with this project directory
pyenv local ml
pyenv activate ml

# upgrade pip and install dependencies
pip install --upgrade pip
pip install -r requirements.txt
```

After these steps you can open the notebooks in jupyter with kernal that uses created environment.

## technologies
python, jupyter, scikit-learn, pytorch, pandas, numpy, matplotlib, scipy, optuna