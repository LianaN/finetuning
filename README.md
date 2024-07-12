# Fine-Tuning Small Language Models
This repository contains a collection of experimentation notebooks for fine-tuning small language models and small vision language models. Fine-tuning the models like `Phi-3-vision-128k-instruct` is especially advantageous because their compact size opens doors for new application scenarios with limited internet connectivity and computational resources. This makes them applicable to domains such as manufacturing, sustainability, healthcare, etc., where deploying AI solutions in resource-constrained environments might be crucial.

The following notebooks are currently available in this repository: 

- `multi-modal-finetuning/phi-3-vision-custom-dataset` demonstrates how to fine-tune `microsoft/Phi-3-vision-128k-instruct` model to identify and describe errors in boxing based on a photo. 

- `multi-modal-finetuning/phi-3-vision-huggingface-dataset` demonstrates how to fine-tune `microsoft/Phi-3-vision-128k-instruct` model to describe technical details of aircrafts (model, fuselage, etc) based on a photo.

## Usage
1. Clone this repository to your machine.
2. Go to the relevant folder e.g. `multi-modal-finetuning/phi-3-vision`
3. Open the README inside the relevant folder and follow the instructions.
