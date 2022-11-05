
## Project: NLP For Finance
<br />

### I completed this project during 2022 summer holidays at [ Inspirit AI ](https://www.inspiritai.com/).
<br />

The problem we were trying to solve is to predict sentiment by analyzing sentence coming out from financial news outlet. Sentiment were labeled as:
```
{
    0: 'negative',
    1: 'neutral',
    2: 'positive'
}
```
I used BERT (Bidirectional Encoder Representations from Transformers), NLP pre-train deep bidirectional unsupervised language representations from unlabeled text by jointly conditioning on both left and right context in all layers, for sentiment analysis. <br />

Pre-trained BERT model “BertForSequenceClassification” is a normal BERT model with an added single linear layer on top for classification that we used as a sentence classifier. As we feed input data, the entire pre-trained BERT model and the additional untrained classification layer is trained on our specific task.
<br />
<br />

***
Reference:
1.	https://arxiv.org/pdf/1810.04805.pdf 
2.	https://arxiv.org/abs/1810.04805
3.	https://huggingface.co/blog/bert-101
4.	https://huggingface.co/transformers/v2.2.0/model_doc/bert.html#bertforsequenceclassification
5.	https://jalammar.github.io/illustrated-bert/
6.	https://www.blog.google/products/search/search-language-understanding-bert/
7.	https://ai.googleblog.com/2018/11/open-sourcing-bert-state-of-art-pre.html
8.	https://www.analyticsvidhya.com/blog/2019/09/demystifying-bert-groundbreaking-nlp-framework/
9.	https://www.analyticsvidhya.com/blog/2021/06/why-and-how-to-use-bert-for-nlp-text-classification/
***