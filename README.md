# MultiTaskBench: COLING 2025

## Citation 

Please consider citing the following paper if you use this code or data in your work:

``` 
@misc{jan2024multitaskmayhemunveilingmitigating,
      title={Multitask Mayhem: Unveiling and Mitigating Safety Gaps in LLMs Fine-tuning}, 
      author={Essa Jan and Nouar AlDahoul and Moiz Ali and Faizan Ahmad and Fareed Zaffar and Yasir Zaki},
      year={2024},
      eprint={2409.15361},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2409.15361}, 
} 
```

## MultiTaskBench Safety Dataset
The MultiTaskBench dataset is available in `datasets/multitaskbench`

The directory contains a `.csv` files, containing the combined 2000 data, 500 queries for each task (Classification, Text Generation, Code Generation and Translation).

## Harmful Testing Dataset
Dataset to measure the Attack Success Rate (ASR) of a model is available in `datasets/harmful`.

## Fine-Tuning Code
The code used to fine-tune open source models is available in `code/Finetuning`.

## GPT Judge Evaluation Code
The code used to evaluate LLM responses is available in `code/evaluation`

## Fine-Tuned Model Access
Models fine-tuned by MultiTaskBench Dataset are available on our [Huggingface](https://huggingface.co/Essacheez/LLAMA3.1-8b-SafetyData-combine-4.8k-default-style).


## Licensing

Code is licensed under the MIT License.

