# nlp-for-punjabi
State of the Art Tokenizer, Language model and Classifier for punjabi language (spoken in Indian sub-continent)

## Dataset
Download Wikipedia Articles Dataset (44,000 articles) which I scraped, cleaned and trained model on from [here](https://www.dropbox.com/sh/dpfvf1gvbxqfwnv/AADp8drS7HopN_1H7D_1vqSOa?dl=0)

Checkout BBC Punjabi News dataset  which I scraped, cleaned and trained model on from the repository path `datasets-preparation/panjabi-bbc-news-dataset/`


## Results

Perplexity of Language Model: ~13 (on 20% validation set)

Kappa Score of classification model: ~49 


## Pretrained Language Model

Download pretrained Language Model from [here](https://www.dropbox.com/s/d0fzov1jw7ogkmq/fourth.pth.zip?dl=0)

## Tokenizer

Unsupervised training using Google's [sentencepiece](https://github.com/google/sentencepiece)

Download the model and vocabulary from [here](https://www.dropbox.com/sh/mj54tvdfaso2okq/AABJMoLN1jYLOawva3RtB5Tba?dl=0)