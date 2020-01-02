# NLP for Punjabi
This repository contains State of the Art Language models and Classifier for
 Punjabi language (spoken in Indian sub-continent)

The models trained here have been used in [Natural Language Toolkit for Indic Languages
 (iNLTK)](https://github.com/goru001/inltk)

## Dataset

#### Created as part of this project
1. [Punjabi Wikipedia Articles](https://www.kaggle.com/disisbig/punjabi-wikipedia-articles)

2. [Punjabi News Dataset](https://www.kaggle.com/disisbig/punjabi-news-dataset)

## Results

#### Language Model Perplexity

| Architecture/Dataset | Punjabi Wikipedia Articles |
|:--------:|:----:|
|   ULMFiT  |  24.40  |
|  TransformerXL |  14.03  |


#### Classification Metrics

##### ULMFiT

| Dataset | Accuracy | Kappa Score |
|:--------:|:----:|:----:|
| Punjabi News Dataset |  89.17  |  54.5  |

#### Visualizations
 
##### Embedding Space

| Architecture | Visualization |
|:--------:|:----:|
| ULMFiT | [Embeddings projection](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/goru001/nlp-for-punjabi/master/language-model/embedding_projector_config.json) |


## Pretrained Language Model

Download pretrained Language Model from [here](https://www.dropbox.com/s/d0fzov1jw7ogkmq/fourth.pth.zip?dl=0)

## Classifier

Download classifier from [here](https://www.dropbox.com/sh/2qe0jcfnxel59g1/AADPeLElM9sbFkyzvTUbEKNUa?dl=0)

## Tokenizer

Unsupervised training using Google's [sentencepiece](https://github.com/google/sentencepiece)

Download the trained model and vocabulary from [here](https://www.dropbox.com/sh/mj54tvdfaso2okq/AABJMoLN1jYLOawva3RtB5Tba?dl=0)

