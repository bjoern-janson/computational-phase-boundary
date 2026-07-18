# Phase Boundary Dataset

## Purpose

The Phase Boundary Dataset is the empirical foundation for testing the Computational Evolution framework.

Its purpose is to evaluate whether major computational paradigm transitions are preceded by measurable increases in aligned information velocity.

The central test is:

$$
\Delta\Lambda_E(t)
\rightarrow
\Delta\alpha(t)
\rightarrow
\Delta C(t)
$$

A successful case should demonstrate:

$$
t_\Lambda < t_\alpha < t_C
$$

within a predefined temporal horizon:

$$
t_C-t_\Lambda<\tau
$$

---

# Dataset Philosophy

The dataset is designed to measure changes in the structure of search processes rather than only changes in final performance.

Traditional technology datasets primarily track:

- benchmark scores
- hardware performance
- investment levels
- adoption rates

This dataset additionally tracks:

- hypothesis-to-feedback velocity
- design-space accessibility
- description-length reduction
- evaluation efficiency
- utility alignment

The goal is to identify whether a system became better at discovering solutions before it became better at producing them.

---

# Data Model

Each historical transition is represented as a state transition:

$$
\mathcal M_{old}
\rightarrow
\mathcal M_{new}
$$

where:

- $\mathcal M_{old}$ is the previous computational interface.
- $\mathcal M_{new}$ is the new interface or mechanism.
- The transition is evaluated for structural change.

---

# Case Record Schema

Each entry should contain:

```yaml
case:
  name:
  domain:
  period:

  old_mechanism:
  new_mechanism:

  timestamps:
    intervention:
    information_velocity_shift:
    accessibility_shift:
    capability_transition:

  metrics:
    lambda_E:
    accessibility:
    description_gain:
    utility_alignment:

  resources:
    compute:
    capital:
    workforce:
    experimental_volume:

  outcome:
    classification:
      # winner
      # false_positive
      # false_negative

  uncertainty:
    confidence:
    evidence_quality:

  sources:
