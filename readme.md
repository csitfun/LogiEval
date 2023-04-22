# LogiEval: a benchmark suite for testing logical reasoning abilities of instruct-prompt large language models

Please refer to our paper "[Evaluating the Logical Reasoning Ability of ChatGPT and GPT-4](https://arxiv.org/abs/2304.03439)" if you are interested in this test suite.

This repository is based on the [OpenAI Eval library](https://github.com/openai/evals). Please download the Eval package first, and put the contents in this repository `Data` and `evals` into `evals/evals/registry/data/<name_of_your_eval/` and `evals/evals/registry/evals/`, respectively.

eg. `evals/evals/registry/data/logiqa/logiqa.jsonl`, `evals/evals/registry/evals/logiqa.yaml`

## Set up
`pip install evals`

## Eval OpenAI models
1. export openai api key to the environment

```export OPENAI_API_KEY=<your_key>```

2. run eval

```oaieval <model_name> <data_name>```

eg. `oaieval gpt-3.5-turbo logiqa`

## How to cite

```
@misc{liu2023evaluating,
      title={Evaluating the Logical Reasoning Ability of ChatGPT and GPT-4}, 
      author={Hanmeng Liu and Ruoxi Ning and Zhiyang Teng and Jian Liu and Qiji Zhou and Yue Zhang},
      year={2023},
      eprint={2304.03439},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
