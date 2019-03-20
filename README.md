# NLP for Punjabi
First ever, State of the Art Tokenizer, Language model and Classifier for Punjabi language (spoken in Indian sub-continent)

NOTE: This is the first ever Language model and Classifier in Punjabi to the best of my knowledge. If you know of some previous work which has been done in NLP for Punjabi, let me know. I'll be happy to correct my statements.

## Dataset
Download Wikipedia Articles Dataset (44,000 articles) which I scraped, cleaned and trained model on from [here](https://www.dropbox.com/sh/dpfvf1gvbxqfwnv/AADp8drS7HopN_1H7D_1vqSOa?dl=0)

Checkout BBC Punjabi News dataset  which I scraped, cleaned and trained model on from the repository path `datasets-preparation/panjabi-bbc-news-dataset/`


## Results

Perplexity of Language Model: ~13 (on 20% validation set)

Kappa Score of classification model: ~60 

Accuracy of classification model: 89%

    Note: Accuracy would be a wrong metric with the above dataset, as it was highly unbalanced, with

    114 Positive Examples
    670 Negative Examples

    Hence, It would be better to look at Kappa Score (~60).

## Pretrained Language Model

Download pretrained Language Model from [here](https://www.dropbox.com/s/d0fzov1jw7ogkmq/fourth.pth.zip?dl=0)

## Classifier

Download classifier from [here](https://www.dropbox.com/sh/2qe0jcfnxel59g1/AADPeLElM9sbFkyzvTUbEKNUa?dl=0)

## Tokenizer

Unsupervised training using Google's [sentencepiece](https://github.com/google/sentencepiece)

Download the trained model and vocabulary from [here](https://www.dropbox.com/sh/mj54tvdfaso2okq/AABJMoLN1jYLOawva3RtB5Tba?dl=0)

