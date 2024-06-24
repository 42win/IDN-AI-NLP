# Project NLP 1 : Sentiment Analysis Piplres 2019

## Goal

Tujuan utama adalah memahami sentimen yang diungkapkan oleh pengguna Twitter selama Pemilihan Presiden 2019 di Indonesia. 
Dengan menganalisis sentimen—positif, netral, dan negatif—dari 1815 tweet, maka akan didapatkan wawasan tentang opini publik dan tren sentimen selama peristiwa politik.

## Code Lab
1. [data Preprocesing & EDA](data_preprocessing_n_EDA.ipynb)
2. [model 1 - transformerEncoder](model_01_transformerEncoder.ipynb)
3. [model 2 - indoBert](model_02_indoBert.ipynb)
4. [model 3 - RoBERTa](model_03_RoBERTa.ipynb)
5. [model 4 - RoBERTa](model_03_RoBERTa.ipynb)

## Hasil Evaluasi
| model                        | training | testing |
|------------------------------|----------|---------|
| transformerEncoder           | 0.94     | 0.61    |
| indo-BERT (base-uncased)     | 0.97     | 0.62    |
| indo-BERT (base-p2)          | 0.66     | 0.42    |
| RoBERTa (roberta-base-indonesian) | 0.72 | 0.59    |
| LSTM                         | 0.96     | 0.50    |
| BiLSTM                       | 0.99     | 0.54    |
| CNN-BiLSTM                   | 0.98     | 0.55    |
| SVM Classifier               | 0.93     | 0.60    |
| Random Forest                | 0.99     | 0.58    |
| GradientBoostingClassifier   | 0.82     | 0.56    |
