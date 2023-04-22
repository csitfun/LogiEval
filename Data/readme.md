# The data directory for storing LogiEval datasets
The LogiEval datasets are adapted from logical reasoning machine reading comprehension and natural language inference datasets:
- Machine reading comprehension
  * LogiQA
  * LogiQA zh
  * LogiQA-ood
  * ReClor
  * AR-LSAT
- Natural Language Inference
  * ConTRoL
  * ConjNLI
  * HELP
  * MED
  * TaxiNLI

The original logical reasoning datasets are converted into instruct-prompt style.

For the machine reading comprehension task, the instruction is:

```Instructions: You will be presented with a passage and a question about that passage. There are four options to be chosen from, you need to choose the only correct option to answer that question. If the first option is right, you generate the answer 'A', if the second option is right, you generate the answer 'B', if the third option is right, you generate the answer 'C', if the fourth option is right, you generate the answer 'D'. Read the question and options thoroughly and select the correct answer from the four answer labels. Read the passage thoroughly to ensure you know what the passage entails.```

For the natural language inference task, the instruction is:

```Instructions: You will be presented with a premise and a hypothesis about that premise. You need to decide whether the hypothesis is entailed by the premise by choosing one of the following answers: 'e': The hypothesis follows logically from the information contained in the premise. 'c': The hypothesis is logically false from the information contained in the premise. 'n': It is not possible to determine whether the hypothesis is true or false without further information. Read the passage of information thoroughly and select the correct answer from the three answer labels. Read the premise thoroughly to ensure you know what the premise entails.```
