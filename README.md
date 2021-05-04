# dlh-project
CS598 Deep Learning for Healthcare Project
## Mortality Prediction of ICU Diabetic Patients Based on Clinical History and Clinical Notes- A Multi-Network Deep Learning Model

### Project Motivation
The goal of the project is to design a deep learning model to predict the mortality of an ICU diabetic patient after 48 hours of admission. The model is a multi-RNN architecture with an attention mechanism that engages clinical notes and specific clinical features to predict mortality.

### Built With
- Python 3
- Pytorch
- Pandas
- Numpy
- AWS Athena
- AWS Sagemaker
- Gensim
- NLTK

### File Description
### Main
- main.ipynb
### Model
- notes_events_network_join.ipynb
### Data File
- sql_queries.ipynb
### Word Embedding Model
- notebook_word2vec.ipynb
### Project Report
-

### Getting Started
- Obtain license for the MIMICIII database from https://physionet.org/content/mimiciii/1.4/
- Helpful link on how to access MIMICIII database on AWS https://aws.amazon.com/blogs/big-data/perform-biomedical-informatics-without-a-database-using-mimic-iii-data-and-amazon-athena/
- Install Anacondas or Python 3, Pytorch, Pandas 1.15, Numpy, Gensim, NLTK
- Get connected to AWS to use AWS Athena to build the tables following instructions in sql_queries.ipynb
- Save data files as pickle
- Load the word embedding model, note_vectors.kv. If you want to rerun the embedding model, run notebook_word2vec.ipynb
- run events_extraction.ipynb
- run notes_extraction.ipynb
- run the main file to execute the model

### Authors
- Olabisi Balogun
- Jorge Flores 
- Francisco Noya 

### License

MIT License

Copyright (c) [2021] [Olabisi Balogun, Jorge Flores,Francisco Noya]

### Acknowledgments
- Choi, Bahadori, Kulas, Schuetz, Stewart and Sun. “RETAIN: An Interpretable Predictive Model for Healthcare using Reverse Time Attention Mechanism”. 2016
- Yang, H., Kuang, L., & Xia, F. (2021). “Multimodal temporal-clinical note network for mortality prediction”. Journal of Biomedical Semantics, 12(1), 1-14
