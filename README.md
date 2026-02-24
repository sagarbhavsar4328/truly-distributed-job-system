# Truly Distributed Job System

# Context and Background

# Decision Drivers

**Rules**
1. No of slices >>= No of workers (pods)
2. Scale parameter/factor = No. of worker
3. Skew < 10% (or shard balancing > 90%)
4. Slice to worker mapping should be deterministic
5. No new index or field
6. Capability to rerun the failed worker.
7. Same data ==> multiple views/reports/filter criteria
8. No of slices should be a base of _[128, 512, 1024]_ and should not change for years.

# Options Considered

# Comparison Summary

# Decision

# Justification

# Consequences
