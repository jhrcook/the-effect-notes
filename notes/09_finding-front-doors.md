# Chapter 9. Finding Front Doors

## 9.1 Looking ahead

- instead of closing all possible back doors, can focus on isolating front doors

## 9.2 Trying to push a string

- if multiple back doors, can *partition the variation* on the treatment
    - can isolate particular sample
    - other statistical adjustments to remove the back door effects
        - randomized controlled experiments: the participants backgrounds have no influence on whether they recieve the treatment
        - but randomization is not always available and these cases are more tricky


## 9.3 What the world can do for us

- *natural experiment*: "a real-world setting in which some sort of randomization has been done for us"
- *source of exogenous variation*: look for a source of variation with no open back doors
- differences between randomized controlled trial and natural experiment:
    1. there can be back doors for the natural experiment; will need to control for them
    1. natural experiments are more natural, removing some potential variation due to the explicit experimental environment
    1. need to remove cases in a natural experiment where the randomness isn't a good assumption
    1. can be difficult to convince others that your exogenous source of variation is truly independent of all other factors
-

## 9.4 Is it too good to be true?

- for an exogenous source of variation, have to assume it is random within the context of the data generating process
    - all studies require assumptions, but some are more believable than others

## 9.5 Riding a shooting star

- *front door method*: a strategy to identify the causal effect of a treatment on an outcome by isolating front doors
    - less frequently used in research than finding an exogenous source of variation


---

## Session information


```python
%load_ext watermark
%watermark -d -u -v -iv -b -h -m
```

    Last updated: 2022-12-02

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
