# passive_investing
This is a repository for analyzing performance of a basket of exchange-traded funds (ETF)


# Exchange-Traded Fund (ETF) Analyzer: new application for Passive Investing

etf_analyzer is a fintech application that helps in analyzing performance of a set of ETF.
 

The current project is the inital design and development of the application to get MVP that can be tested on the current market cycle.

---

## Technologies

This project leverages python 3.7 with the following packages:
* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entry-point.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

* [Jupyter](https://jupyter.org/documentation) - For documentation

* [sqlalchemy](https://docs.sqlalchemy.org/en/14/core/engines.html#sqlite) - For more info on SQLite

* [voila](https://github.com/voila-dashboards/voila/tree/main/docs) - for documentation
---

## Installation Guide

Before running the application first install the following dependencies.

```python
  pip install fire
  pip install questionary
  pip install jupyterlab
  conda list sqlalchemy
  conda install -c conda-forge voila
```
run the web application by typing the following url on your web browser

https://mybinder.org/v2/gh/odhissm/passive_investing.git/HEAD

---

## Usage

To use the loan qualifier application simply clone the repository and run the **app.py** with the:

```jupyter
from command line type

jupyter lab
```

---

## Contributors

Brought to you by odhissm@gmail.com

---

## Image of voila application

![etf_analyzer Application](etf_analyzer/Resources/images/web_app.jpg)

## License

MIT
