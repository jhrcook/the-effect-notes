# Chapter 8. Causal Paths and Closing Back Doors

## 8.1 Walk the line

- *path*: the series of arrows and nodes to follow to get from one variable to another
- can have multiple paths between two variables


## 8.2 Any way you like it

- good to cover all possible paths from treatment to outcome variables
    - each path is a story about how one variable can have knock-on effects

## 8.3 Good paths and bad paths, front doors and back doors

- good vs. bad paths
    - "good paths": relationships between the treatment and outcome variables that *should* count for the research question
    - "bad paths": relationships between the treatment and outcome variables that *should not* count for the research question
front vs. back doors
    - "front door path": paths where all the arrows point away from the treatment
    - "back door path": paths where some arrows point towards the treatment
- relating good/bad and front/back:
    - front door paths are usually good
    - back door paths are usually bad
- key to answering our research question is how to isolate just the good paths out of the data without getting distracted by the bad paths


## 8.4 Open and closed paths

- a path is *open* if the variables are allowed to vary
    - the path is *closed* if at least one variable is constant
- there multiple ways to close a path
    - a simple one is to select/filter a dataset such that a variable is constant
    - control for the variable
- *collider*: a variable in a path that only has arrows pointing at it
    - a path with a collider is automatically closed
    - controlling for the collider opens the path
- the goal: to identify the answer to a research question, need to open the good paths and close the bad paths


## 8.5 Using paths to test your diagram

- can analyze other paths besides those for our research question in order to test the diagram's structure
- for variables $A$ and $B$, close all possible paths then measure the correlation of the values
    - if any correlation remains, then the model is missing some relationships
- *placebo tests*: testing that a relationship is 0 where we expect it to be based on the diagram
- failing these tests is not critical, depends on the how deficient the model is
    - can sometimes be safely ignored


---

## Session information


```python
%load_ext watermark
%watermark -d -u -v -iv -b -h -m
```

    Last updated: 2022-12-01

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

    sys: 3.10.8 | packaged by conda-forge | (main, Nov 22 2022, 08:27:35) [Clang 14.0.6 ]




```python

```
