# Fine-Tuning Phi-3-vision-128k-instruct
This folder contains a Jupyter notebook for fine-tuning the `microsoft/Phi-3-vision-128k-instruct` language model for multi-modality tasks.

## Usage
1. Install the required Python libraries from `requirements.txt`:
```
pip install -r requirements.txt
```
2. Open the Jupyter notebook `Phi_3_Vision_Fine_tuning.ipynb` and follow the instructions provided within the notebook.

## Model Details
- Model name: `microsoft/Phi-3-vision-128k-instruct`
- Model card in Hugging Face: https://huggingface.co/microsoft/Phi-3-vision-128k-instruct

## Dataset
The dataset for fine-tuning consists of two CSV files that define the training and validation entries. Additionally, there are sample images located in `multi-modal-finetuning/phi-3-vision/images`. You can organize your dataset in a similar structure. The sample CSV files in `multi-modal-finetuning/phi-3-vision` demonstrate the required structure and must be extended with more entries for a valid fine-tuning experiment.

Here's an example of the CSV format:
```
userPrompt;imageURL;assistantResponse
What kickboxing mistake is the person making in the picture?;images/image3.jpg;The individual's back foot appears to be too light on the floor, suggesting a lack of proper weight distribution. This can lead to a decrease in power and stability during punches.
```

**Feel free to adapt this structure to your specific task and add more entries as needed.**