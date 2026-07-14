# RLBench Closed-Loop Reports

Static reports for RLBench closed-loop inference experiments.

## Diffusion Policy

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

## LingBot-VA

- Report: [docs/lingbot-va-inference-report/index.html](docs/lingbot-va-inference-report/index.html)
- Variants: `rgb-action`, `rgb-depth-flow-action`
- Episodes: 10 seeds per completed run, seed base `930000`
- Current completed latest-run total: `0/50`

The report includes completed and in-progress run status, per-episode outcome tables, and selected final comparison videos.
