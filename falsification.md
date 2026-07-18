# Falsification Criteria

## Purpose

This document defines the conditions under which the Computational Evolution framework would be considered unsupported or falsified.

The framework is only meaningful if its predictions can fail.

The central empirical claim is:

> In major computational paradigm transitions, aligned information velocity should increase before realized capability growth.

The theory does not claim that every increase in search efficiency produces a revolution. It claims that genuine structural transitions require detectable changes in the search process before downstream capability expansion.

---

# 1. Primary Causal Falsification

The core predicted ordering is:

$$
\Delta\Lambda_E
\rightarrow
\Delta\alpha
\rightarrow
\Delta C
$$

or:

$$
t_\Lambda < t_\alpha < t_C
$$

The theory fails if historical analysis demonstrates that:

$$
t_C \leq t_\Lambda
$$

in a substantial fraction of major paradigm transitions.

## Interpretation

If capability improvements consistently appear before measurable changes in information velocity or accessibility, then the framework's causal direction is incorrect.

The alternative explanation would be:

- capability is primarily driven by resource scaling,
- random discovery,
- institutional factors,
- or external shocks.

---

# 2. False Negative Test

A false negative occurs when:

$$
\Delta C \gg 0
$$

while:

$$
\Delta\Lambda_E \leq 0
$$

## Meaning

A technology achieves a major capability transition without any measurable increase in:

- information extraction efficiency,
- utility alignment,
- iteration velocity,
- or search-space accessibility.

## Consequence

Repeated false negatives would invalidate the central hypothesis that computational progress is mediated by transformations of the search process.

---

# 3. False Positive Test

A false positive occurs when:

$$
\Delta\Lambda_E > 0
$$

but:

$$
\Delta C \approx 0
$$

after the predefined temporal horizon:

$$
t_C-t_\Lambda>\tau
$$

## Meaning

The system becomes dramatically better at generating and evaluating knowledge but fails to produce a capability transition.

Possible explanations:

- incorrect utility alignment estimation,
- missing selection pressure variables,
- inaccessible deployment pathways,
- incorrect assumption about causal relevance.

A high rate of false positives would indicate that information velocity is not sufficient as a predictor.

---

# 4. Temporal Horizon Failure

The framework requires a bounded delay:

$$
t_C-t_\Lambda<\tau
$$

The parameter $\tau$ must be fixed before evaluating outcomes.

The theory fails if:

- the delay window must repeatedly be extended after observing results,
- different cases require arbitrary horizons,
- no stable domain-dependent calibration exists.

An infinite delay would make the framework unfalsifiable.

---

# 5. Resource Scaling Confound Test

A major vulnerability is confusing structural change with increased resources.

The framework predicts:

$$
\frac{\partial\Lambda_E}{\partial r}_{structural}
\gg
\frac{\partial C}{\partial r}
$$

A failure occurs if:

$$
\Delta C
$$

is fully explained by:

- increased compute,
- increased capital,
- increased workforce,
- increased experimental volume,

without any improvement in information efficiency per unit resource.

In this case, the transition is classified as exploitation rather than structural evolution.

---

# 6. Description Length Failure

Structural transitions should produce:

$$
\Delta L_\chi>0
$$

where:

$$
\Delta L_\chi
=
L(\mathcal D|M_{old})
-
L(\mathcal D|M_{new})
$$

A failure occurs if a supposed breakthrough:

- does not reduce conditional description length,
- does not absorb complexity into the mechanism,
- does not reduce human/system specification burden.

Such cases indicate ordinary optimization rather than a search-space transformation.

---

# 7. Alignment Failure

The framework requires:

$$
\Delta A(U|O,\mathfrak C)>0
$$

A technology may generate information without producing useful progress.

Examples:

- benchmark exploitation,
- irrelevant correlations,
- optimization toward flawed objectives.

If these cases regularly appear indistinguishable from genuine transitions, then the alignment factor is insufficient.

---

# 8. Geometry Failure

The framework predicts that structural events modify the search geometry:

$$
\chi:
(g,n,U)
\rightarrow
(g',n',U')
$$

A failure occurs if major transitions are consistently explained without changes to:

- representational distance,
- accessibility,
- searchable dimensionality,
- evaluation efficiency.

This would imply that geometry is unnecessary and progress follows simpler mechanisms.

---

# 9. Cross-Domain Failure

The theory claims a general mechanism across computational domains.

Validation should therefore include multiple categories:

- software abstraction
- machine learning
- hardware systems
- scientific computing
- engineering design

The framework weakens substantially if it only works within a single domain.

---

# 10. Selection Pressure Failure

The framework includes environmental selection:

$$
S
$$

A technology with high information velocity should not necessarily dominate unless it aligns with external constraints.

However, if selection pressure completely explains every transition while information velocity adds no predictive value, then the framework provides no additional explanatory power.

---

# 11. Predictive Benchmark

The strongest test is prospective prediction.

Given a set of candidate technological basins:

1. Estimate $\Lambda_E$.
2. Estimate accessibility acceleration.
3. Rank predicted transition likelihood.
4. Observe future capability development.

The theory succeeds only if these rankings outperform:

- random prediction,
- resource-only models,
- investment-based models,
- historical trend extrapolation.

---

# 12. Minimal Survival Condition

The framework survives only if:

1. Information velocity precedes capability growth.
2. The lead time is bounded.
3. The effect survives resource controls.
4. False positives are manageable.
5. The signal generalizes across domains.

Formally:

$$
\boxed{
\Delta\Lambda_E
>
0
\Rightarrow
\Delta C
>
0
\quad
\text{within}
\quad
\tau
}
$$

under controlled comparison against resource-driven explanations.

---

# Conclusion

The Computational Evolution framework is falsifiable because it makes a temporal and causal commitment:

Capability explosions are not the first visible event.

They are the downstream consequence of earlier transformations in the efficiency of exploration itself.

If empirical evidence shows otherwise, the framework should be rejected.
