# Snapdragon Research

[Open the dashboard](https://lcardencmu.github.io/snapdragon-research-status/) · [Owner conversation](https://github.com/lcardenCMU/snapdragon-research/issues)

Bring up the existing four-engine profiler, establish safe local assistance, then begin precommitted research.

Platform: **HDK8750 MP**. Updated: 2026-10-31T19:54:56.264035+00:00

| Engine | Readiness |
| --- | --- |
| CPU | Correctness smoke passed |
| GPU | Correctness smoke passed |
| DSP | SDK setup needed |
| NPU | SDK setup needed |

Tests: 48. PDFs retrieved: 50/111 (unverified).

## Now

- CPU and GPU correctness smoke checks passed
- Owned local runtime and Qwen3 1.7B installed; host calibration still gated
- Independent private evidence archive verified; research workflow integration

## Next

- Resolve practical headroom calibration without weakening the host guard
- Verify Qualcomm DSP/NPU runtime and SDK compatibility
- Read priority paper methods and freeze the research evaluation task bank

## Blockers

- Conservative host guard currently refuses local inference
- Available student DSP skeleton targets a different Hexagon ISA
- Qualcomm SDK/runtime setup remains incomplete

Architecture findings: 0. Controlled AI research tasks: 0. Setup is excluded from research-benefit metrics.
