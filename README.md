# Diffusion Policy RLBench Results

Static report for Diffusion Policy closed-loop RLBench inference.

- Report: [docs/dp-inference-report/index.html](docs/dp-inference-report/index.html)
- Baseline: Diffusion Policy
- Action mode: absolute
- Episodes: 10 seeds per task, seed base `930000`

| Task | Success |
| --- | ---: |
| `place_cups` | `0/10` |
| `place_shape_in_shape_sorter` | `0/10` |
| `stack_blocks` | `0/10` |
| `stack_cups` | `0/10` |

The report includes the per-task `sweep_summary.json`, metrics JSON, and all saved observation videos.
