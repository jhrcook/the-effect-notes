# Chapter 11. Causality with Less Modeling

## 11.1 Confidence

- model is likely wrong, but give it a shot (I think this is what this section was saying?)

## 11.2 Wide open spaces

- sometimes there are so many back doors that you can control for them all without controlling for any of them (?)
    - the explanation of this is not clear to me
- with a lot of possible back doors, closing some may close many others so they should be prioritized
- can sometimes assume things are comparable without explicitly controlling for the variation
    - select a control group and compare against the treatment
    - need to select specific comparisons to make sure not just comparing treated vs. untreated
        - (except in randomized controlled experiments)

## 11.3 Yes, I'm wrong, but am I that wrong?

- difficult to test is assumptions are correct, easier instead to test if they are false
- robustness test:
    1. "checking whether we can disprove an assumption"
    1. "redoing our analysis in a way that doesn’t rely on that assumption and seeing if the result changes"
- common robustness test is that we claim there is no relationship between $X$ and $Y$ so we test if there is a measurable relationship
    - test for the presence of a relationship that an assumption implies shouldn't exist
- all assumptions are incorrect at some level
    - more important to find out *how* wrong they are
- *partial identification*: make assumptions we are very confident in, then use a range of possibilities for the remaining assumptions and produce an estimate for the effect over that range
    - need not make assumptions until we identify the effect, instead just produce estimates for each possible case of the remaining back doors
    - depending on the remaining assumptions, the estimate may be an upper or lower bound on the effect
- generally good to finish with a "gut check" or "sanity check"


---

## Session information


```python
%load_ext watermark
%watermark -d -u -v -iv -b -h -m
```

    Last updated: 2022-12-05

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
