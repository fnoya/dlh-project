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
### Model
- notes_events_network_join.ipynb
### Data File
- sql_queries.ipynb
### Word Embedding Model
- notebook_word2vec.ipynb
### Project Report
-

### Getting Started
- Install Anacondas or Python 3, Pytorch, Pandas 1.15, Numpy, Gensim, NLTK
- Get connected to AWS to use AWS Athena to build the tables following instructions in sql_queries.ipynb
- Save data files as pickle
- Load the word embedding model, note_vectors.kv. If you want to rerun the embedding model, run notebook_word2vec.ipynb
- run the note_events_network_join.ipynb 
- You can run individual network - **
