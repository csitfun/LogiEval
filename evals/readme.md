# This is the directory for storing eval registers

Register the eval by adding a file to `evals/registry/evals/<eval_name>.yaml`

```
<eval_name>:
  id: <eval_name>.dev.v0
  metrics: [accuracy]

<eval_name>.dev.v0:
  class: evals.elsuite.basic.match:Match
  args:
    samples_jsonl: <eval_name>/samples.jsonl
```
