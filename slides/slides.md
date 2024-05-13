---
marp: true
---

# Exploratory Data Analysis

## Polars way

### PyCon Italia, 2024

---

### About Me

Jan Pipek

---

## Intro

---

### What is polars?

- Library for manipulation with tabular data*
- Contender to pandas (and many more similar tools)
- Since 2020, started by Ritchie Vink

---

### Why polars?

- Performance (rust)
- Clean(er) API
- Lazy evaluation & query optimization
- Cool kid on the block

---

### Why not polars?

- Less stable
- Less functionality
- Less known
- Sometimes lengthy code

--- 

### Exercise time

```shell
jupyter lab
```

Open "exercises/10-exploration.ipynb"

---

## Basic types

---

### DataFrame

- a "table"?
- a "spreadsheet" table?
- a "dict of columns"?

---

### Series

- a "list"?
- a "column"?
- an "array of "X"?

---

### D(ata) types

- distinct from (but convertible to/from) Python classes
- numerical values (int / float, various precision), strings, dates, datetimes

---

## Basic plotting

Note: Requires [hvplot](https://hvplot.holoviz.org/)

---

```python
df.plot(x=)
df.plot.bar
df.plot.scater
```

---

### Exercise time

---

## Filtering & Sorting

---

```python
data.filter(
    # Expression
    pl.col("column") > 0
)
```


```python
data.filter(
    # Shortcut
    column="value"
)
```

---

```python

data.sort(
    "column"
)

```

---

## Operations

---

### Arithmetics

```python
.select(
    *expressions,
    **named_expressions,
)
```

---

### Manipulation 

- The series are read-only.
- DataFrames are (almost read-only).

---

## Aggregations 

### a.k.a. `.group_by`

---


---

## Joins

### a.k.a. `.merge`

---

## (Extra) Wide/long data format

---

.melt

---

.pivot
