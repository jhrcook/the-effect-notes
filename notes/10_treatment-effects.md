# Chapter 10. Treatment Effects

## 10.1 For whom the effect holds

- a treatment can have a range of effects
- thus, can estimate the distribution of effects

## 10.2 Treatment averages

- concept that each subject has their own treatment effect
    - collectively forms a distribution of treatment effects
- *average treatment effect* (ATE): average of the treatment effect across the popultation
    - often a useful metric of the distribution of treatment effects
- multiple ways to measure:
    1. measure the average effect in only some members of the population or conditional on some attribute
    1. measure the effect in every member of the population, but count some individuals more than others


## 10.3 I just want an ATE, it would make me feel great, what do I get?

- "The treatment effect we get is almost entirely determined by the source of treatment variation we use."
    - e.g. for an experiment, are limited to the variation in the subjects we include
- Rules of Thumb:
    1. "If you have true randomization in a representative sample and don’t need to do any adjustment, you have an *average treatment effect* (ATE)."
    1. "If you have true randomization only within a certain group, and you isolate that group so you can take advantage of that randomization, you have a *conditional average treatment effect*."
    1. "If you know that some variation in treatment is connected to back doors and so you close those back doors, using only the remaining variation, you have a *weighted average treatment effect*..."
    1. "If you are identifying your effect by assuming that some untreated group is what the treated group would look like if they hadn’t been treated, then we have the *average treatment on the treated* (ATT)."
    1. "If part of the variation in treatment is driven by an exogenous variable, and you isolate just the part driven by that exogenous variable, then you have a *local average treatment effect* (LATE)."

## 10.4 Who cares?

- we care about causal effects because we want to estimate the predicted effect if we intervene
    - the type of treatment effect average we have changes how we interpret what it means to intervene
    - should consider what treatment average effect we measure based on what the intervention could/would look like


---

## Session information


```python
%load_ext watermark
%watermark -d -u -v -iv -b -h -m
```

    Last updated: 2022-12-04

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
