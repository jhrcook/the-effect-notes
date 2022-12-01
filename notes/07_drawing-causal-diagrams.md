# Chapter 7. Drawing Causal Diagrams

## 7.1 Our idea of the world

- need to do research on the topic in order to understand the system

## 7.2 Thinking through the data generating process

- need to isolate just the relevant factors
    - cannot build a model of the entire world

## 7.3 Simplify

- once a causal diagram has been constructed, look for places to simplify
    - removing some minor details may make the model easier to interpret and thus more useful
- look for the following characteristics:
    1. *unimportance*: likely to have a small/negligible effect
    1. *redundancy*: variables that occupy the same space in the model (they have the same inputs and outputs); often best to combine these variables
    1. *mediators*: mediators that only exist to link two other observed variables can usually be dropped
    1. *irrelevance*: requires knowledge about the system; can be identified by looking for variables that do not have a path to the outcome variables

## 7.4 Avoiding cycles

- a causal diagram cannot have cycles
    - cannot start from one variable, fallow any connections, and eventually return to the original variable
- this would mean that a variable causes itself
- many cases that seem contrary to this remain consistent when you recall that the events are organized in time

## 7.5 Getting comfortable with assumptions

- assumptions appear in the diagram because of missing knowledge
    - can never know everything, so there will always be assumptions
- recommendation is to be critical and reasonable
    - open to criticism from others – may be able to fill in the gaps of missing knowledge
- there are various ways of testing some types of assumptions, too, that will be covered later

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
