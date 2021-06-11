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
# Solutions

**Task 1**

```{code-cell} ipython3
n1,n2,n3 = 3,-4,6

print(n1,n2,n3)

r1 = (2 * n1 + 3 * n2)*2 - 5 *n3
print(r1)
```

**Task 2**

```{code-cell} ipython3
total1 = 0
total2 = 0

for i in range(3,52,3):
    total1 = total1 + i
    total2 += i # shorter form

print("The summation is",total1)
print("The summation is",total2)
```

**Task 3**

```{code-cell} ipython3
T = 0
n = 2  # this value iteratively will be first halved and then added to the summation T
number_of_iteration = 1
number_of_terms = 0

while T<=1.99:
    n = n/2 # half the value of n
    print("Iteration =",number_of_iteration,"and n =",n)
    T = T + n # update the value of T
    print(" T =",T)
    print(" Is T less than or equal to 1.99? -",(T<=1.99))
    number_of_terms = number_of_terms + 1
    number_of_iteration +=1
    print()

print()
print("The number of terms in the summation:",number_of_terms)
```