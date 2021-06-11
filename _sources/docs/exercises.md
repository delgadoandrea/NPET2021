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
# Exercises

## Task 1

Define three variables *n1*, *n2*, and *n3*, and set their values to *3*, *-4*, and *6*.

Define a new variable *r1*, and set its value to *(2 X n1 + 3 X n2) X 2 - 5 X n3*, where X represents the multiplication operator. 

The multiplication operator in python (and in many other programming languages) is * .

Then, print the value of *r1*. 

**As you may verify it by yourself,  the result should be -42**.

```{code-cell} ipython3
Insert your code here
```

## Task 2

Calculate the value of summation *3+6+9+...+51*, and then print the result.

**Your result should be 459.**

```{code-cell} ipython3
Insert your code here
```

## Task 3
```{code-cell} ipython3
<a id="task3"></a>
<h3> Task 3 </h3>

Consider the summation $ T(n) = 1 + \dfrac{1}{2} + \dfrac{1}{4}+ \dfrac{1}{8} + \cdots + \dfrac{1}{2^n} $ for some natural number $ n $. 

Remark that $ T(0) = \dfrac{1}{2^0} = \dfrac{1}{1} = 1 $.

This summation can be arbitrarily close to $2$. 

Find the minimum value of $ n $ such that $ T(n) $ is close to $2$ by $ 0.01 $, i.e., $ 2 - T(n) < 0.01 $.

In other words, we find the minimum value of $n$ such that $ T(n) > 1.99 $.

The operator for "less than or equal to" in python is "$ < = $".

```

```{code-cell} ipython3
Insert your code here
```
