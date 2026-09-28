# Project-HAMi Contributions

**Organization:** Project-HAMi  
**Repository:** [Project-HAMi/HAMi](https://github.com/Project-HAMi/HAMi)

## Merged Pull Requests

### [#2740 — Fix invalid device count across accelerator backends](https://github.com/Project-HAMi/HAMi/pull/2740)
Fixed invalid device-count validation across eight accelerator backends: Biren, Cambricon, Kunlun, Vastai, NVIDIA, Iluvatar, AWS Neuron, and Metax.

- Rejected zero and negative device counts instead of allowing them to bypass GPU quota validation.
- Added upper-bound validation against `math.MaxInt32`.
- Added regression coverage for boundary and invalid values across affected backends.
- Verified backend tests, formatting, and diff checks.

## Engineering Themes

Go · Kubernetes device plugins · accelerator resource validation · regression testing · GPU scheduling