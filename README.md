# Experimental-Validation
Experimental validation of the functional information framework through controlled role, weight, and recursive state-transition experiments.

This repository contains the experimental implementation of the CogMI
functional information framework.

## Framework

Each information element is represented as:

\[
E_i = (I_i, R_i, w_i)
\]

where:

- \(I_i\) — information content
- \(R_i\) — functional role
- \(w_i\) — influence weight

The generative transition is conceptually represented as:

\[
G_{t+1}
=
\sigma
\left(
\sum_i w_{i,t}\phi(I_{i,t},R_{i,t})
\right)
\]

## Experiments

The notebook contains four controlled experiments:

1. **Same Information, Different Roles**
2. **Sensory Weight Dominance**
3. **Memory Weight Dominance**
4. **Recursive Generative State Transition**

The experiments examine the effects of information content, functional
role, influence weight, and previous generative state.

## Notebook

The complete experimental implementation is available in:

`CogMI_Experimental_Validation.ipynb`

## Reproducibility

API credentials are not included in this repository. They are supplied
through the execution environment using secure Colab secrets.

Because generative model outputs can vary between executions, the
analysis focuses on behavioral patterns under controlled experimental
conditions rather than requiring identical textual outputs.

## Status

Research prototype.
