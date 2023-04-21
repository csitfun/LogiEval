# LogiEval: a benchmark suite for testing logical reasoning abilities of instruct-prompt large language models

This repository is based on the [OpenAI Eval library](https://github.com/openai/evals).

## Set up
`pip install evals`

## Eval OpenAI models
1. export openai api key to the environment
`export OPENAI_API_KEY=<your_key>`
2. run eval
`oaieval <model_name> <data_name>`
eg. `oaieval gpt-3.5-turbo logiqa

