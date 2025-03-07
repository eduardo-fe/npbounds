# npbounds

**npbounds** is a Stata command that computes Manski's bounds under three sets of assumptions—NAB (No Assumption Bounds), MTR (Monotone Treatment Response), and MTS (Monotone Treatment Selection). It implements the inferential method developed in Chenozhukov et al. to provide robust inference in partially identified models.

## Features

- **Multiple Assumptions:** Computes Manski's bounds under:
  - **NAB:** No Assumption Bounds (i.e., worst-case bounds)
  - **MTR:** Monotone Treatment Response
  - **MTS:** Monotone Treatment Selection
- **Robust Inference:** Implements the inferential method from Chenozhukov et al. for constructing confidence intervals and hypothesis testing in the partial identification context.
- **Bootstrap Options:** Allows for bootstrap replications to improve the accuracy of the inference.

## Installation

There are two ways to install **npbounds**:

### 1. Using the `net install` command

In Stata, run:
```stata
net install npbounds, from("https://github.com/yourusername/npbounds")
