# Fine-Tuning Small Language Models
This repository contains a collection of experimentation notebooks for fine-tuning a small vision language model called `Phi-3-vision-128k-instruct`. The Phi-3-Vision is a lightweight, state-of-the-art model developed by Microsoft and capable of understanding multimodal data. It's designed to be efficient, with a smaller number of parameters (4.2B) compared to larger models, yet still delivers high-quality results. It supports long-context prompts up to 128K tokens. Phi-3-Vision can be deployed on edge and cloud platforms.

Fine-tuning small vision language models like `Phi-3-vision-128k-instruct` is especially advantageous because their compact size opens doors for new application scenarios with limited internet connectivity and computational resources. This makes them ideal for specific domains such as manufacturing, sustainability, healthcare, etc., where deploying AI solutions in resource-constrained environments might be crucial.

The following notebooks are currently available in this repository: 

- `multi-modal-finetuning/phi-3-vision-custom-dataset` demonstrates how to fine-tune `microsoft/Phi-3-vision-128k-instruct` model to identify and describe errors in boxing based on a photo. 

- `multi-modal-finetuning/phi-3-vision-huggingface-dataset` demonstrates how to fine-tune `microsoft/Phi-3-vision-128k-instruct` model to describe technical details of aircrafts (model, fuselage, etc) based on a photo.

## Usage
1. Clone this repository to your machine.
2. Go to the relevant folder e.g. `multi-modal-finetuning/phi-3-vision`
3. Open the README inside the relevant folder and follow the instructions.
