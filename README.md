# NLP for Punjabi
This repository contains State of the Art Language models and Classifier for
 Punjabi language (spoken in Indian sub-continent)

The models trained here have been used in [Natural Language Toolkit for Indic Languages
 (iNLTK)](https://github.com/goru001/inltk)

## Dataset

#### Created as part of this project
1. [Punjabi Wikipedia Articles](https://www.kaggle.com/disisbig/punjabi-wikipedia-articles)

2. [Punjabi News Dataset](https://www.kaggle.com/disisbig/punjabi-news-dataset)

#### Open Source Datasets
1. [IndicNLP News Article Classification Dataset - Punjabi](https://github.com/ai4bharat-indicnlp/indicnlp_corpus#indicnlp-news-article-classification-dataset)

## Results

#### Language Model Perplexity (on validation set)

| Architecture/Dataset | Punjabi Wikipedia Articles |
|:--------:|:----:|
|   ULMFiT  |  24.40  |
|  TransformerXL |  14.03  |


#### Classification Metrics

##### ULMFiT

| Dataset | Accuracy | MCC | Notebook to Reproduce results |
|:--------:|:----:|:----:|:----:|
| IndicNLP News Article Classification Dataset - Punjabi |  97.12  |  96.17  | [Link](https://github.com/goru001/nlp-for-punjabi/blob/master/classification/Panjabi_Classification_Model.ipynb) |

#### Visualizations
 
##### Word Embeddings

| Architecture | Visualization |
|:--------:|:----:|
| ULMFiT | [Embeddings projection](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/goru001/nlp-for-punjabi/master/language-model/embedding_projector_config.json) |
| TransformerXL | [Embeddings projection](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/goru001/nlp-for-punjabi/master/language-model/embedding_projector_transformer_config.json) |


##### Sentence Embeddings

| Architecture | Visualization |
|:--------:|:----:|
| ULMFiT | [Encodings projection](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/goru001/nlp-for-punjabi/master/language-model/sentence_encodings/encoding_projector_config.json) |

## Pretrained Models

#### Language Models 

Download pretrained Language Models from [here](https://drive.google.com/open?id=1GXqqBEqja-KT3XG3UfZWNbl2vCb7aD3g)

#### Tokenizer

Unsupervised training using Google's [sentencepiece](https://github.com/google/sentencepiece)

Download the trained model and vocabulary from [here](https://www.dropbox.com/sh/mj54tvdfaso2okq/AABJMoLN1jYLOawva3RtB5Tba?dl=0)

