# KubeEdge / Ianvs Contributions

**Organization:** Cloud Native Computing Foundation (CNCF) / KubeEdge  
**Repository:** [kubeedge/ianvs](https://github.com/kubeedge/ianvs)

## Summary

Contributed fixes and developer tooling to the Ianvs distributed AI benchmarking framework. Work focused on configuration correctness, dependency handling, CI validation, cross-platform execution, and documentation/examples.

## Merged / Submitted Contributions

### CI example configuration validation
Built `scripts/validate_example_configs.py`, a dependency-free validator that checks each example's configuration → algorithm → module reference chain against the framework's real contracts.

**Validation:** introduced deliberate invalid configurations to confirm the validator fails with exit code 1, then restores the configuration and confirms exit code 0.

### PIPL privacy-preserving LLM tutorial restoration — #704
Restored a broken tutorial example by:
- replacing a nonexistent PyPI dependency;
- correcting configuration/schema mismatches with the actual Algorithm/Module contract;
- removing unused ClassFactory registrations;
- constructing the real framework objects to validate the fix instead of relying only on static inspection.

### Configuration path-resolution fixes
Traced the framework's configuration-loading implementation and identified that example paths resolve relative to the repository root rather than the referencing file.

Applied the root-cause fix across affected examples.

### Other contribution areas
Additional PRs covered:
- Apple Silicon / non-CUDA compatibility;
- optional-dependency detection;
- `__all__` mismatches;
- field-type validation;
- runtime dependency declarations;
- dead-code removal.

## Engineering Themes

Python · configuration systems · dependency management · CI validation · framework internals · regression testing · cross-platform debugging