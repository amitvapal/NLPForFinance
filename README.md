
## Project: NLP For Finance
<br />

### I completed this project during 2022 summer break at [ Inspirit AI ](https://www.inspiritai.com/).
<br />

I used Bidirectional Encoder Representations from Transformers (BERT, pre-trained NLP model) model for sentiment analysis to predict whether the stock price will go up or down. 

Given datasets
- finance_train.csv
- finance_test.csv

Sentiments were labeled as:
```
{
    0: 'negative',
    1: 'neutral',
    2: 'positive'
}
```
Then I used “BertForSequenceClassification” from transformers package from Hugging Face which gave PyTorch interface for working with BERT. This is the normal BERT model with an added single linear layer on top for classification that we will use as a sentence classifier. As we feed input data, the entire pre-trained BERT model and the additional untrained classification layer is trained on our specific task. 


### Certificate of completion
<img src="amitvaPal-2022-inspiritAI-certificate.jpg">

<br />
<br />

***
Reference:
1.	https://arxiv.org/pdf/1810.04805.pdf 
2.	https://arxiv.org/abs/1810.04805
3.	https://huggingface.co/blog/bert-101
4.	4.https://huggingface.co/transformers/v2.2.0/model_doc/bert.html#bertforsequenceclassification
5.	https://jalammar.github.io/illustrated-bert/
6.	https://jalammar.github.io/a-visual-guide-to-using-bert-for-the-first-time/
7.	https://www.blog.google/products/search/search-language-understanding-bert/
8.	https://ai.googleblog.com/2018/11/open-sourcing-bert-state-of-art-pre.html
9.	https://www.analyticsvidhya.com/blog/2019/09/demystifying-bert-groundbreaking-nlp-framework/
10.	https://www.analyticsvidhya.com/blog/2021/06/why-and-how-to-use-bert-for-nlp-text-classification/

***