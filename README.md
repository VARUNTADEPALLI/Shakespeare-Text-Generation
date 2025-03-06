
# Shakespeare Text Generation with Transformers

This project implements a character-level text generation model using a transformer architecture to generate Shakespeare-like text. The model is trained on the "tiny Shakespeare" dataset and leverages multi-head self-attention, positional embeddings, and feed-forward layers to predict and generate text sequences.

---

## **Project Overview**
The goal of this project is to build a transformer-based language model that can generate text in the style of Shakespeare. The model operates at the character level, predicting the next character in a sequence given the previous characters. It is trained using PyTorch and includes features like multi-head self-attention, positional embeddings, and a training loop with periodic evaluation.

---

## **Features**
- **Character-Level Modeling**: Predicts the next character in a sequence, enabling fine-grained text generation.
- **Transformer Architecture**: Utilizes multi-head self-attention and positional embeddings to capture long-range dependencies in text.
- **Training and Evaluation**: Includes a training loop with periodic evaluation on both training and validation sets to monitor performance.
- **Text Generation**: Generates new text in real-time after training, mimicking the style of the input dataset.
- **Customizable Parameters**: Allows tuning of hyperparameters like batch size, sequence length, learning rate, and model dimensions.

---

## **Installation**
To run this project, you need to have Python and PyTorch installed. Follow these steps:

1. Download the google colab notebook and run the cells.
