# TUTORIAL: Sentiment analysis on Tweets using Hugging Face

The aim of this tutorial is to use NLP to analyse sentiments on Tweets.

We will compare 3 different [Hugging Face](https://huggingface.co/) models:
- model based on [camemBERT](https://huggingface.co/transformers/model_doc/camembert.html): [pt-tblard-tf-allocine](https://huggingface.co/philschmid/pt-tblard-tf-allocine)
- model based on [BARThez](https://huggingface.co/transformers/model_doc/barthez.html): [barthez-sentiment-classification](https://huggingface.co/moussaKam/barthez)
- model based on [BERT](https://huggingface.co/transformers/model_doc/bert.html): [bert-base-multilingual-uncased-sentiment](https://huggingface.co/nlptown/bert-base-multilingual-uncased-sentiment)


### Sentiment Analysis with pt-tblard-tf-allocine

*Théophile Blard, **French sentiment analysis with BERT**, (2020), [GitHub repository](https://github.com/TheophileBlard/french-sentiment-analysis-with-bert)*

Tweets are divided into 2 classes according to their sentiment: **positive** or **negative**.

![camemBERT_results](https://github.com/eleapttn/Hugging-Face-sentiment-analysis-twitter-AI-Notebooks-OVHcloud/blob/main/images-results/results-camembert.png)

### Sentiment Analysis with barthez-sentiment-classification

*Eddine, Moussa Kamal and Tixier, Antoine J-P and Vazirgiannis, Michalis, **BARThez: a Skilled Pretrained French Sequence-to-Sequence Model**, (2020), [GitHub repository](https://github.com/moussaKam/BARThez)*

Tweets are divided into 2 classes according to their sentiment: **positive** or **negative**.

![BARThez_results]()

### Sentiment Analysis with bert-base-multilingual-uncased-sentiment

*Refer to [NLP Town](https://www.nlp.town/)*

Tweets are divided into 5 classes, from 1 to 5 stars, according to their sentiment: 1 star corresponds to a **very negative** tweet while 5 stars corresponds to a **very positive** tweet.

![BERT_results](https://github.com/eleapttn/Hugging-Face-sentiment-analysis-twitter-AI-Notebooks-OVHcloud/blob/main/images-results/results-bert.png)
