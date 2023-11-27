# Trainer_ru_summarization_Lenta_mT5

Trainer for model mT5 for task to summarize news post. Training on data grabbed from russian news site Lenta.ru.

Обучающий блокнот для модели mT5 для задачи суммаризации новостных статей. Обучение проводилось на данных, полученных с русского новостного сайта Lenta.ru.

## Model Details

### Model Description

<!-- Provide a longer summary of what this model is. -->
- **Developed by:** [i-k-a](https://huggingface.co/i-k-a)
- **Shared by:** [i-k-a](https://huggingface.co/i-k-a)
- **Model type:** Transformer Text2Text Generation
- **Language(s) (NLP):** Russian
- **Finetuned from model:** mT5-base

### Model Sources

<!-- Provide the basic links for the model. -->
- **Repository:** [link](https://huggingface.co/i-k-a/ru_summarization_lenta_model_mt5-base_7_epochs_1024/tree/main)

## Training Details

Model trained 7 epochs. Length of input text is cut to 1024 tokens. Output is 400 tokens.
Trained using Google Colab resources.

## Technical Specifications

### Model Architecture and Objective
google/mt5-base

### Compute Infrastructure
Google Colab

#### Hardware
Google Colab T4 GPU

#### Software
Python