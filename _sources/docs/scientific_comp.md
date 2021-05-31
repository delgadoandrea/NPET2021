---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.10.3
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

(launch/thebe)=
# Getting Started

This module is designed to introduce you to the basic commands and tools needed to run your first scientific computing application. We will start with basic commands to execute in a Unix Shell, followed by a short tutorial on Python. But before we start, let's get you all set-up.

## Setting up your terminal

## Running code 

Some sections will allow you to run code and see outputs *without leaving the page*. Interactivity is provided
by a kernel running on the public [**MyBinder**](https://mybinder.org) service.

For an example, click the {fa}`rocket` --> {guilabel}`Live Code` button above on this page, and run the code below.

```{code-cell} ipython3
import numpy as np
import matplotlib.pyplot as plt
plt.ion()

x = np.arange(500)
y = np.random.randn(500)

fig, ax = plt.subplots()
ax.scatter(x, y, c=y, s=x)
```



