# titanicLesson
A machine learning [notebook](src/main.ipynb) on how predict which passengers survived the Titanic shipwreck

## Running locally

The notebook uses ***Python 3.8.6***

### Installing Pipenv

The notebook uses Pipenv for dependency management, which can be installed by running

```bash
pip install pipenv
```

There are several other ways to install Pipenv. Please follow 
[the official guide](https://pipenv.pypa.io/en/latest/install/#installing-pipenv) to see all possible options.

### Installing dependencies
When inside the project directory, the dependencies can be installed by running

```bash
pipenv install
```

Alternatively, you can install them manually by running


```bash
pip install pandas scikit-learn matplotlib seaborn jupyterlab
```

### Running notebook
The notebook can be launched either by running

```bash
pipenv run lab
```
 or 
 ```bash
jupyter lab src/main.ipynb
```
depending on how dependencies were installed.