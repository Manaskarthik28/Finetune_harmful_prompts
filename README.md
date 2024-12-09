# Finetune_harmful_prompts
Finetune harmful prompts using Llama 3.1 8B
# Project Title: Multilingual Prompt Classification for Safety Filtering Using LLaMA 3.1 8B and LoRA Fine-Tuning

# Objective:  
The primary goal of this project is to develop a model that classifies prompts as "safe" or "unsafe" based on their labels, using a dataset consisting of 133 multilingual prompts. These prompts, originating from a variety of languages, are combined into a single dataset for processing. The model is fine-tuned using LLaMA 3.1 8B with the LoRA technique to enhance prompt filtering across multiple languages.

# Dataset:  
The dataset includes prompts in 133 different languages, with each prompt labeled as either "safe" or "unsafe." The data from these diverse languages are merged into one unified file for analysis. The dataset columns are as follows:  
- new_id: Unique identifier for each row.  
- prompt: The actual question or statement in the prompt.  
- label: The classification label ("safe" or "unsafe").  
- data_source: The source from which the dataset was collected.  
- old_id: The original identifier of the row before merging.  
- language: The language in which the prompt is written.

The fine-tuned model aims to efficiently classify and filter unsafe prompts, ensuring improved safety across diverse languages.

For learning more about llama 3.1 8b please refer to this link: https://huggingface.co/meta-llama/Llama-3.1-8B
For learning more about finetune using lora please refer to this link: https://arxiv.org/abs/2106.09685
For dataset you can be find link here: https://huggingface.co/manas2804/manasfinetune/blob/main/new_merged_languages.csv

