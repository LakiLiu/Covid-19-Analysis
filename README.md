# Covid-19-Analysis

### 1. Covid-19 Human Behaviour Analysis: A creative Reseach
##### (A) Description:
- Herd Behavior is commonly used in Financial Markets to predict uncertainty. 
- Common Models : Econometrics Regression  and Time Series 
- Research Value :  Very Rarely applied in the Covid-19 Mobility case but Human behavior uncertainty affects the policy effectiveness 

#### (B) Model:
- Baseline Model : Bayesian Ridge Regression

---
### 2. Covid-19 Sentiment Analysis: A Chinese NLP Study
##### (A) Description:
- The dataset was based on 230 keywords related to the topic of COVID, and a total of 1 million blogs were collected from 1 January 2020 to 20 February 2020. THis includes sentiments : 1 (positive), 0 (neutral) and -1 (negative)
(数据集依据与“新冠肺炎”相关的230个主题关键词进行数据采集，抓取了2020年1月1日—2020年2月20日期间共计100万条微博数据，并对其中10万条数据进行人工标注，标注分为三类，分别为：1（积极），0（中性）和-1（消极）)
- 评价指标 Evaluation Matrix: Macro-F1 score

#### (B) Model:
- Preprocessing：tokenisation, remove duplicate, remove similar words
- Machine Learning Model: Naive Bayes, Logistic regression -> result F1 score : 0.74
- Deep Learning Model：RNN (RNN+LSTM)， CNN

