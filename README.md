# Mental Health Counseling Conversational Chatbot 

This repository contains the implementation of a mental health chatbot, fine-tuned on LLaMA 2 using QLoRA. The chatbot is designed to help users identify and manage stress through meaningful and empathetic interactions.  

## Features  
- **Empathetic Conversations**: The chatbot identifies user stressors and suggests ways to manage them.  
- **Task Prioritization**: Guides users to prioritize and organize tasks for better workload management.  
- **Interactive Support**: Offers relaxation techniques, coping strategies, and self-care tips.  

## Files in the Repository  

- **`Demo.mp4`**: A demo video showcasing the chatbot in action.  
- **`fine_tuning_with_llama_2_qlora (1) (1).py`**: Python script used to fine-tune LLaMA 2 with QLoRA.  
- **`llm-project-bot.ipynb`**: Jupyter notebook that integrates the chatbot with Telegram for interactive use.  
- **`llm-project-inference-from-fine-tuned-model (1) (1).ipynb`**: Notebook for performing inference using the fine-tuned model.  
- **`trained-model.zip`**: A zip file containing the fine-tuned LLaMA 2 model for deployment.  

## Screenshots  
 
[Chat Interface 1](Images/interface_english.png)  [Chat Interface 2](Images/interface_english_2.png)  

## Setup Instructions  

1. **Load the Fine-Tuned Model**
Extract the contents of `trained-model.zip` and place them in the `models/` directory.

2. **Run the Telegram Interface**
Use the `llm-project-bot.ipynb` notebook to deploy the chatbot on Telegram. Configure the bot token in the notebook before running it.

3. **Inference**
Test the chatbot locally by running the inference notebook `llm-project-inference-from-fine-tuned-model (1) (1).ipynb`.

## Evaluation Results  

The fine-tuned model was evaluated on metrics commonly used for natural language understanding tasks. Below are the scores:  
[Results For English](Images/results_english.png)  [Results For Hindi](Images/results_hindi.png)  


