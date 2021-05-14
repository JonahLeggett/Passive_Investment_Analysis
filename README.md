# Passive_Investment_Analysis
Analysis of Passive Investments (ETF's)
In this analysis I've built a financial database and web application by using SQL, Python, and the Voilà library to analyze the performance of an ETF portfolio. The portfolio consists of four stocks: GOST, GS, PYPL, and SQ. Each stock has its own table in the etf.db database, which the Resources folder also contains. I analyze the daily returns of the ETF stocks both individually and as a whole. Then I deploy the visualizations to a web application by using the Voilà library.

---

## Technologies

This project leverages python 3.7 with the following packages:


* [pandas1.2.4](https://pandas.pydata.org) - Open source data analysis and manipulation tool, built on top of the Python programming language.

* [hvplot.pandas](https://hvplot.holoviz.org/user_guide/Pandas_API.html) - A high-level plotting API for the PyData ecosystem built on HoloViews.

* [numpy](https://numpy.org) -T he fundamental package for scientific computing with Python.

* [sqlalchemy](https://www.sqlalchemy.org) - SQLAlchemy is the Python SQL toolkit and Object Relational Mapper that gives application developers the full power and flexibility of SQL.
---

## Installation Guide

Before running the application first install the following dependencies.

```python
pip install pandas
-AND-
jupyter lab
-AND-
pip install SQLAlchemy
-AND-
pip install hvplot
```

---

## Usage

To use the San Francisco Housing Analysis simply clone the repository and run the **etf_analyzer.ipynb** with:

```python
jupyter lab
```
-OR-

run the following code in your terminal:
```python
voila etf_analyzer.ipynb
``` 

---

## Contributors

Brought to you by Jonah A. Leggett. You can reach me at jonah.leggett@gmail.com 

You can add me at LinkedIn: (https://www.linkedin.com/in/jonah-l-29278a8a/)

---

## License

mit
