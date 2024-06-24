# Project NLP 1 : Sentiment Analysis Piplres 2019
![image](https://github.com/42win/IDN-AI-NLP/assets/55066281/fa0a1e50-e212-4130-b7d3-0da9472b213c)

## Goal

Tujuan utama adalah memahami sentimen yang diungkapkan oleh pengguna Twitter selama Pemilihan Presiden 2019 di Indonesia. 
Dengan menganalisis sentimen—positif, netral, dan negatif—dari 1815 tweet, maka akan didapatkan wawasan tentang opini publik dan tren sentimen selama peristiwa politik.

## Dataset
dataset yang digunakan adalah kumpulan data sentiiment yang berasal dari pengguna twitter saat pelaksanaan PILPRES 2019 lalu.
[dataset](https://github.com/42win/IDN-AI-NLP/tree/main/project-01-sentiment-analysis/dataset)

## Code
1. [data Preprocesing & EDA](data_preprocessing_n_EDA.ipynb)
2. [data Preprocesing 2](data_preprocessing_2.ipynb)
3. [model 1 - transformerEncoder](model_01_transformerEncoder.ipynb)
4. [model 2 - indoBert](model_02_indoBert.ipynb)
5. [model 3 - RoBERTa & LSTM](Model_03_RoBerta_n_LSTM.ipynb)
6. [model 4 - CNN-BiLSTM](Model_04_CNN_BiLSTM.ipynb)
7. [model 5 - BiLSTM](Model_05_Bi_LSTM.ipynb)
8. [model 6 - SVM & RandomForest](Model_06_SVM_n_RandomForest_TFIDF.ipynb)
9. [model 7 - GradientBoosting](Model_07_Gradien_Boosting.ipynb)

## Hasil Evaluasi (Accuracy)
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
