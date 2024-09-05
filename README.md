# Question Answering with DistilBERT

This project demonstrates the use of the distilbert-base-uncased-distilled-squad model for question answering using the Hugging Face Transformers library. It evaluates the model's performance using various prompt designs.

# Table of Contents

• Installation

• Usage

• Evaluation

• Results

• Contributing

• License

• Installation

To use this project, you'll need to install the required Python packages. Ensure you have transformers, datasets, and numpy installed. You can install these packages using pip.

# Usage

# 1.Prepare Your Inputs:

  • Text (Context): The text from which the model will extract the answer.
  
  • Question: The question you want the model to answer.
  
  • Reference Answer: The correct answer used for evaluating the model's responses.
  
# 2.Run the Script:

  • Input the context, question, and reference answer as prompted.
  
  • The script will generate answers based on different prompt styles and evaluate their accuracy.
  
# Evaluation

The project evaluates the model's performance by comparing its generated answers against a reference answer. It measures accuracy across various prompt designs to understand how different styles impact the model's responses.

# Results

Results are presented as accuracy scores for each prompt style. These scores reflect how well the model performs with different types of prompts, helping to gauge its effectiveness and adaptability.

