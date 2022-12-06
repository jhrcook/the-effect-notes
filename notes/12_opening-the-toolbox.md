# Chapter 12. Opening the Toolbox

## 12.1 Concept and execution

- second half of the book concerned with putting the theory from the first half into practice
- commonly need to figure out which of a selection of tools fits our problem
    - still starts with understanding the data generating process and building a causal diagram

## 12.2 The toolbox chapters

- chapters 16-20 focus on the "template" research designs
    - tools for common structures of causal diagrams (i.e. experimental designs)
    - these chapters will have the same three sections:
        1. "How does it work?"
        1. "How is it performed?"
        1. "How the pros do it."
- recommends *Causal Inference: The Mixtape* by Scott Cunningham for up-to-date applications of these methods

## 12.3 Code examples

- examples available in R, Python, Stata
    - (I'll be sticking with the Python examples)
    - the installation of the `causaldata` package from PyPI is included in the creation of the virtual environment for this repository
- example use case of getting information from the `mortgages` dataset


```python
from causaldata import mortgages

print(mortgages.DESCRLONG)
```

    The mortgages data contains data from Fetter (2015) on home ownership rates by men, focusing on whether they were born at the right time to be eligible for mortgage subsidies based on their military service. This data was used in the Regression Discontinuity chapter of The Effect.



```python
print(mortgages.NOTE)
```

    ::
        Number of observations - 214144
        Number of variables - 6
        Variables name definitions::
                bpl - Birth State
                qob - Quarter of birth
                nonwhite - White/nonwhite race indicator. 1 = Nonwhite
                vet_wwko - Veteran of either the Korean war or World War II
                home_ownership - Owns a home
                qob_minus_kw - Quarter of birth centered on eligibility for mortgage subsidy (0+ = eligible)



---

## Session information


```python
%load_ext watermark
%watermark -d -u -v -iv -b -h -m
```

    Last updated: 2022-12-06

    Python implementation: CPython
    Python version       : 3.10.8
    IPython version      : 8.6.0

    Compiler    : Clang 14.0.6
    OS          : Darwin
    Release     : 21.6.0
    Machine     : x86_64
    Processor   : i386
    CPU cores   : 4
    Architecture: 64bit

    Hostname: JHCookMac.local

    Git branch: master

    causaldata: 0.1.3
    sys       : 3.10.8 | packaged by conda-forge | (main, Nov 22 2022, 08:27:35) [Clang 14.0.6 ]




```python

```
