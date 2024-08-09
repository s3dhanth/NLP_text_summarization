
# Enhanced Text Summarization bot using Custom training of Model Pegasus

This repository contains a FastApi application for an enhanced Q&A bot that leverages Pegasus model and FastApi. The app allows users to interact with the Model and get responses based on their queries.

## DataSet

- SAMSum dataset contains about 16k messenger-like conversations with summaries
- Data Splits
- train: 14738
- test: 819

## Pegasus Model

- The Pegasus model, developed by Google Research, is a large and sophisticated transformer-based model designed specifically for abstractive text summarization.

- Number of Parameters: Approximately 568 million.
- Layers: 16 Transformer layers in both the encoder and decoder.
- Hidden Size: 1024 hidden units.
- Attention Heads: 16 attention heads.

## Installation

1. Clone the repository:

```sh
git clone https://github.com/your-username/NLPtextSummarization.git
cd NLPtextSummarization
Install the required dependencies:
sh
Copy code
pip install -r requirements.txt

Usage
To Run the app:
sh
Copy code
run app.py

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgements
Streamlit
OpenAI
LangChain
```
## To use pretrained Model (Samsum dataset) 

- Enter the text you want to summarize and enter execute
 ![image](https://github.com/user-attachments/assets/9a80291b-3d2d-4787-9582-7a28bbc7fda4)

 ## To custom Train the model
 - Paste the dataset to artifacts/dataset and execute
 ![Screenshot 2024-08-09 143442](https://github.com/user-attachments/assets/6da70466-74d3-4076-8733-217c7ad9bf63)

