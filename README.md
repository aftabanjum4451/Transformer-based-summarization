# Transformer-based-summarization
In my response, I used some pre-trained models for summarization, as well as trained the T5 model on custom data.

## Pre trained Models
- T5
- GPT2
- PEGASUS
- Bart
- XLM Transformers
- BigBird Pegasus

All the pre-trained model code can seen on this jupyter notbook "Pre_train_Summarization_models.ipynb".

## Trained T5 model on news summary data set

Trained T5 model in news summary data set 
- Model layout
  - load the data
  - Tranform the data into token ids and mask ids
  - creat data train and test loader
  - load the T5 model
  - Fine tune the T5 model on news data
  - check the quality of generated summary 
