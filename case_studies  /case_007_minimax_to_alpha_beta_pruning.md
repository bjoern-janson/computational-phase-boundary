# Case #7: Minimax → Alpha-Beta Pruning

**Domain:** Artificial Intelligence / Game Search  
**Transition:** Exhaustive game-tree search → optimized search through pruning  
**Classification:** Strong candidate structural transition

---

## Hypothesis

Alpha-beta pruning produced a phase boundary by transforming the geometry of search.

The predicted causal chain:

```
ΔL_chi → ΔΛ_E → Δα → ΔC
```

with bounded transition latency:

```
τ < ∞
```

The core mechanism:

> Alpha-beta pruning reduces the effective search space without changing the optimal decision, converting brute-force exploration into structured search.

---

# Pre-Transition Regime

## Minimax Search

The minimax algorithm evaluates game trees by recursively exploring possible future states.

Characteristics:

- explores branches to a fixed depth,
- evaluates possible outcomes,
- selects optimal moves assuming perfect opposition.

The primary limitation:

```
branching factor ↑
→
search cost ↑ exponentially
```

The system faced a large computational burden because many branches had to be explicitly considered.

High effective description length:

```
L_chi(search space)
```

because useful decision-making required accounting for large portions of the game tree.

Result:

- shallow search depth,
- limited practical strength,
- high computation cost.

---

# Structural Intervention

## Alpha-Beta Pruning (~1950s–1960s)

Alpha-beta pruning introduced bounds that allow the algorithm to eliminate branches that cannot affect the final decision.

The transformation:

Before:

```
Game State
→
Explore All Relevant Branches
→
Evaluate Outcome
```

After:

```
Game State
→
Search + Bounds
→
Ignore Irrelevant Branches
→
Evaluate Outcome
```

The key property:

The final minimax result remains unchanged under perfect conditions.

The improvement comes entirely from search efficiency.

---

# CPB Mapping

## 1. Description Length Absorption

Prediction:

```
ΔL_chi > 0
```

Alpha-beta pruning transfers complexity from exhaustive enumeration into structural constraints.

The system no longer needs to explicitly explore every possible continuation.

Result:

- smaller effective search representation,
- reduced computational burden,
- greater efficiency.

---

## 2. Information Velocity Increase

Prediction:

```
ΔΛ_E > 0
```

The system extracts more useful information per unit computation.

Effects:

- deeper search,
- faster evaluation,
- improved move quality,
- greater iteration efficiency.

The improvement is not from additional resources.

It comes from increasing the value obtained from existing computation.

---

## 3. Search Basin Expansion

Prediction:

```
Δα > 0
```

Alpha-beta pruning expands the reachable search space.

Previously:

```
available compute
→
limited search depth
```

After:

```
same compute
→
deeper effective search
```

The geometry of the search landscape changes by shortening the path to strong solutions.

---

# Capability Transition

Alpha-beta pruning enabled practical high-performance chess engines.

Historical impact:

- stronger chess programs,
- deeper tactical analysis,
- foundations for later systems.

Examples:

- Mac Hack
- later Deep Blue architectures

Without efficient pruning, minimax alone would remain computationally impractical at high search depths.

The key shift:

```
search capability
-----------------
computation used

↑
```

---

# Temporal Validation

Expected ordering:

```
χ_g → ΔΛ_E → Δα → ΔC
```

Observed:

| Event | Period |
|---|---|
| Minimax development | 1940s–1950s |
| Alpha-beta pruning | 1950s–1960s |
| Strong practical chess programs | 1970s–1990s |
| Deep Blue era | 1990s |

Transition latency:

```
τ ≈ decades
```

consistent with bounded domain transitions.

---

# Resource Controls

## Compute Scaling

Hardware improvements contributed to stronger chess engines.

However, alpha-beta pruning provides a clean structural control:

The same computation produces substantially better results.

The improvement is:

```
algorithmic leverage
```

rather than:

```
resource increase
```

This makes it a lower-confound case than modern AI scaling.

---

# Assessment

| Criterion | Result |
|---|---|
| Clear structural intervention | ✅ |
| Historical traceability | ✅ |
| ΔL_chi mechanism | ✅ |
| ΔΛ_E mechanism | ✅ |
| Δα expansion | ✅ |
| Bounded τ | ✅ |
| Resource confound | Low |
| Overall classification | Strong candidate |

---

# CPB Interpretation

Alpha-beta pruning represents a search geometry transformation:

```
χ_g:
brute-force enumeration
→
structured search
```

The system does not become more capable by searching harder.

It becomes more capable because the representation of the search problem improves.

---

# Conclusion

Minimax → Alpha-beta pruning provides strong support for the CPB mechanism:

```
ΔL_chi
→
ΔΛ_E
→
Δα
→
ΔC
```

It is a particularly clean example because the capability improvement comes from structural efficiency rather than increased resources.

Alpha-beta pruning demonstrates the core CPB pattern:

```
complexity absorption
→
higher information velocity
→
expanded search space
→
capability transition
```
