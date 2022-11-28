# Chapter 3. Describing Variables

## 3.1 Descriptions of variables

- empirical research questions really come down entirely to describing the density distributions of statistical variables

## 3.2 Types of variables

- common types of variables:
    - *continuous*: can take any value, often limited to a range
    - *count*: positive integers
    - *categorical*: values are restricted to a set of classes
    - *binary*: categorical variable restricted to $0$ or $1$
    - *ordinal*: ordered categorical variables; some are "more" than others, but not necessarily by consistent intervals
    - *qualitative*: "catch-all" category for everything else; mix of quantitative and categorical

## 3.3 The distribution

- *distribution*: a description of how often different values occur

## 3.4 Summarizing the distribution

- parameterize the the distribution to describe it with specific values
    - need to make assumptions on the type of distribution the variable conforms to
- can take certain percentiles (e.g. 0%, 50%, 100%) or the variance to describe the variability in a distribution
- skew measures the unevenness in the distribution around the center (mean, median, mode)
    - how symmetric the distribution is
    - sometimes, best to *transform* the data to remove skew, that is, to make the distribution symmetric and easier to use/parameterize

## 3.5 Theoretical distributions

- difference between *true* and *observed* distributions
    - eventually just need to say that the observed is a good enough approximation
    - the goal of statistics is to say how generalizable our collected (observed) data is to the true underlying distribution
- some notations:
    - English/Latin letters represent data (e.g. $x$)
    - modifications of English/Latin letters represent calculations done with real data (e.g. $\bar{x}$ is the mean of $x$)
    - Greek letters represent *the truth* (e.g. $\alpha$, $\beta$)
        - some common ones (not always their meaning, but usually):
            - $\mu$: mean
            - $\sigma$: standard deviation
            - $\rho$: correlation
            - $\beta$: regression coefficients
            - $\epsilon$: error terms
    - modifications of Greek letters represent our estimate of *the truth* (e.g. the estimate of $\mu$  is $\hat{\mu}$)
- think of the observed data as coming from the theoretical ("true" or "underlying") distributions
- some key theoretical distributions: *normal distribution* and *log-normal distribution*

---

## Session information


```python
%load_ext watermark
%watermark -d -u -v -iv -b -h -m
```

    Last updated: 2022-11-28

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




```python

```
