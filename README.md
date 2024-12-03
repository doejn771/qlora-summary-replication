# QLoRA in Code Summarization: How Far Are We?
We conduct the first empirical investigation into QLoRA, focusing specifically on method-level code summarization as a representative task that requires the model to identify patterns and structures across both natural and programming languages. Our study evaluates three state-of the-art CLMs across two programming languages: Python and Java. 

#### Fine-tuning

* ##### How to set up the Anaconda environment
  1. `conda env create -n qlora -f conda_environment.yml`
  2. `conda activate qlora`

* ##### Datasets
  The datasets for the evaluation can be found [here](https://huggingface.co/datasets/doejn771/code_x_glue_ct_code_to_text_java_python)
