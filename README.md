# Mistral Dialogue Summarization  

This project involves fine-tuning the **Mistral-7B** model for dialogue summarization using the **SAMSum dataset**. The fine-tuning process is conducted in a **GPU-accelerated environment** using Google Colab.  

## Project Description  

Dialogue summarization is essential for extracting key insights from conversations, such as customer support chats, interviews, or casual dialogues. This project fine-tunes the **Mistral-7B** model on the **SAMSum dataset**, a widely used benchmark for dialogue summarization. Fine-tuning is performed on a **T4 GPU** provided by **Google Colab** for efficient training and inference.  

## Features  

- **Pretrained Mistral Model** – Uses **Mistral-7B**, a powerful transformer model.  
- **SAMSum Dataset** – A dataset containing human-written summaries of dialogues.  
- **Fine-tuning Support** – Allows customization for specific tasks.  
- **Colab-Optimized** – Utilizes free GPU resources.  

## Setup and Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/jay-p007/Mistral-dialogue-summarization-.git
   cd Mistral-dialogue-summarization-
   ```  

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  

3. Obtain a Hugging Face token from [Hugging Face](https://huggingface.co/settings/tokens) and configure it in the notebook.  

## Dataset  

- **SAMSum dataset**: This dataset contains **16,000 dialogues** with human-annotated summaries. It is designed to train models for **abstractive dialogue summarization**.  
- Preprocessing includes **tokenization, padding, and truncation** using the Hugging Face `datasets` library.  

## Usage  

1. Open the `Finetuning_of_Mistral_Model.ipynb` notebook in Jupyter or Google Colab.  
2. Follow the instructions to:  
   - Load and preprocess the **SAMSum dataset**.  
   - Configure hyperparameters for fine-tuning.  
   - Train and evaluate the model.  
3. Generate summaries by running inference on new dialogues.  

## Expected Output  

Example input dialogue from SAMSum:  
```
John: Hey, are we meeting today?  
Alice: Yes, let's meet at 6 PM.  
John: Perfect! See you then.  
```  
### Model-generated summary:  
**"John and Alice plan to meet at 6 PM."**  

## Acknowledgements  

- **SAMSum dataset** from [Hugging Face](https://huggingface.co/datasets/samsum).  
- **Mistral-7B model** for summarization.  
- **Google Colab** for GPU resources.  

## Contributing  

Contributions are welcome! If you’d like to improve the project, feel free to:  
- Submit pull requests.  
- Report issues.  
- Suggest enhancements.  

## License  

This project is licensed under the **MIT License**.  
