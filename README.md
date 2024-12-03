# QLoRA in Code Summarization: How Far Are We?
We conduct the first empirical investigation into QLoRA, focusing specifically on method-level code summarization as a representative task that requires the model to identify patterns and structures across both natural and programming languages. Our study evaluates three state-of the-art CLMs across two programming languages: Python and Java. 

#### Fine-tuning

* ##### How to set up the Anaconda environment
  1. `conda env create -n qlora -f conda_environment.yml`
  2. `conda activate qlora`

* ##### Datasets
  The dataset used for the evaluation can be found [here](https://huggingface.co/datasets/doejn771/code_x_glue_ct_code_to_text_java_python)

* ##### QLoRA fine-tuning 💻
  The code to fine-tune models using QLoRA is provided here:
  - [QLoRA Fine-Tuning](https://github.com/doejn771/qlora-summary-replication/tree/main/qlora)

* ##### Full fine-tuning
  The code for full parameter fine-tuning is provided here:
  - [Full Parameter Fine-Tuning](https://github.com/doejn771/qlora-summary-replication/tree/main/full_finetuning)
 
* ##### Analysis 📊
  To run an analysis on the resulting fine-tuned models, you can use the scripts provided here:
  - [Analysis](https://github.com/doejn771/qlora-summary-replication/tree/main/model_analysis)
