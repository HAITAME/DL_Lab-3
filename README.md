# DL_Lab-3


This repository contains code for two tasks: text classification using PyTorch's Sequence Models and fine-tuning GPT-2 for text generation.

## Part 1: Arabic Text Classification

### Objective
The main purpose of this part is to perform text classification on Arabic text data collected from various websites. The collected data is preprocessed and used to train different sequence models such as RNN, Bidirectional RNN, GRU, and LSTM. The trained models are then evaluated using standard metrics and the BLEU score.

### Workflow
1. **Data Collection**: Use web scraping libraries (Scrapy / BeautifulSoup) to collect text data from Arabic websites on a specific topic.
2. **Data Preprocessing**: Preprocess the collected data by tokenization, stemming, lemmatization, stop words removal, and discretization.
3. **Model Training**: Train RNN, Bidirectional RNN, GRU, and LSTM architectures on the preprocessed data, tuning hyperparameters to achieve the best performance.
4. **Model Evaluation**: Evaluate the trained models using standard metrics and the BLEU score to assess their performance.

## Part 2: Text Generation with GPT-2

### Objective
In this part, the GPT-2 pre-trained model is fine-tuned on a custom dataset for text generation. The fine-tuned model is then used to generate new paragraphs based on a given sentence.

