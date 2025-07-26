# scikit-learn-practice

scikit-learn-practice is a quick refresher on machine learning concepts and algorithms, following the [freeCodeCamp](https://www.youtube.com/watch?v=0B5eIE_1vpU) course.


# Installation

Requirements: Python 3.8

Normally, I would set up a `pyproject.toml`, automated tests, and a CI/CD pipeline. However, since this is just a practice project, we'll keep things simple.

> [!NOTE]
> The course specifically requires `scikit-learn==0.23.0`, which is not compatible with Python 3.9 or newer. This version is used to demonstrate the `load_boston()` dataset, which contains racially insensitive data and has been removed from later releases. For notebooks that do not use this dataset, you can likely use a newer version of Python and scikit-learn.

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
