# NLP-on-Fedspeak-data

Project Overview

This repository contains a dataset comprising 200 Federal Reserve (Fed) statements and meeting minutes, meticulously annotated and classified into five distinct categories by expert analysts. These categories include:

Mostly Dovish
Dovish
Neutral
Hawkish
Mostly Hawkish
To enhance the model's performance, approximately 1200 additional training samples have been added to the original GPT data. The data augmentation was carried out without fine-tuning the prompt.

Two different approaches have been employed for classification:

GPT Data without Finetuning the Prompt:

Prompt: "I will give you an example of how a text is classified as 'dovish,' 'mostly dovish,' 'mostly hawkish,' and 'hawkish.'"
GPT Data with Finetuning the Prompt:

Prompt: "You are an expert in economic modeling and policy analysis, holding a master's degree in finance and economics. You excel at deriving policy implications in plain language easily understood by non-experts."
Additionally, the FinBert algorithm has been utilized for classification alongside GPT-3, showcasing the versatility of approaches within the project.

Instructions for Replication

To replicate the experiment and explore the results, follow the steps outlined in the documentation. The repository provides a comprehensive understanding of the dataset, training process, and evaluation metrics. Feel free to contribute, experiment, or adapt the code for your specific use case. We welcome collaboration and feedback to enhance the robustness of the model.
