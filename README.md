# scikit-learn-practice

scikit-learn-practice is a quick refresher of machine learning concepts and algorithms, following the [freeCodeCamp](https://www.youtube.com/watch?v=0B5eIE_1vpU) course.

# Installation

I'd normally create a `pyproject.toml`, automatic tests and a CI/CD pipeline, but this is just a practice repository, so let's keep it simple.

Requirements: Python 3.8

> The tutorial requires `scikit-learn==0.23.0` specifically, which is not compatible with Python 3.9+). The goal was to demonstrate the `load_boston()` dataset, which contains racially insensitive data and was thus removed from newer releases. For notebooks not using this dataset, a higher version of Python and scikit-learn could likely be used.

```sh
git clone https://github.com/ryouze/scikit-learn-practice.git
```

```sh
cd scikit-learn-practice
```

```sh
python3 -m venv ./env
```

```sh
. env/bin/activate
```

```sh
pip3 install -r requirements.txt
```
