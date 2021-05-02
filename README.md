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
event





Two RNN are constructed.  One on the clinical notes and the other on the events from selected chart events and lab events.
The embedding resulting from the two RNNs are concatenated and feed into a fully connected layer to do the final classification.
