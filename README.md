Grammar Correction Model Using Generative AI

This project aims to develop a grammar correction model using both LSTM-based and GPT-2 generative AI techniques. The primary objective is to automatically correct grammatical errors in sentences by leveraging machine learning and deep learning models.

Project Overview

Data Preprocessing: The dataset, containing ungrammatical and corrected sentence pairs, was tokenized using BERT's WordPiece tokenizer and split into training, validation, and test sets.
Baseline Model: An LSTM-based sequence-to-sequence model was built using GloVe embeddings. Despite reaching a training accuracy of 93%, it showed limitations in correcting grammatical errors accurately.
Enhanced Model: A GPT-2 model was fine-tuned on the dataset, outperforming the LSTM model with a higher BLEU score and better grammatical corrections.
Performance Analysis: The GPT-2 model proved more effective, while the LSTM model struggled with longer sequences and complex grammatical structures.

Enhancements for LSTM Model

Several strategies are suggested to improve the LSTM model's accuracy:
Add additional LSTM layers and increase hidden units.
Incorporate attention mechanisms.
Increase the embedding dimension.
Apply dropout and regularization techniques.

Next Steps

Fine-tune the GPT-2 model further using a larger, more diverse dataset.
Implement the proposed enhancements to the LSTM model.
Conduct human evaluations for a more comprehensive assessment.

Key Findings

Transformer-based models like GPT-2 show greater potential for grammar correction tasks.
With enhancements, the LSTM model could see improved accuracy and generalization.
