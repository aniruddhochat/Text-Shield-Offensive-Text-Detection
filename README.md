## Text Shield: Offensive Text Detection

### Introduction
In today’s digital age, social media platforms have become a common avenue for communication, but unfortunately, they have also become a breeding ground for hate speech and offensive language. 

The prevailing methods of detection of hate speech like lexical detection tend to have lower precision in detecting hate speech since they rely on a few particular keywords and phrases flagged as hate speech. 

Such traditional methods of detecting hate speech can be effective but often miss out on subtle nuances and implicit forms of hate speech.

Therefore, we have proposed an NLP-based approach using Robustly Optimized BERT Approach (RoBERTa) that can detect not only explicit and direct forms of hate speech but also subtle and implicit forms. 

By taking into account the broader context in which the language is used, our model can better differentiate between language that is intended to be harmful and language that is not.

### Dataset

We aggregated data from the following sources:
1. Automated Hate Speech Detection
[Dataset Link][1]

2. Cyberbullying Data 
[Dataset link][2]

3. Twitter Sentiment Analysis
[Dataset Link][3]

4. HatespeechData 
[Dataset Link][4]


### Algorithm and Modelling

We know that transformers were introduced because of their efficiency in text detection where they are able to learn long range dependencies between text tokens. 

This is important for text detection because text can be arranged in a variety of ways, and transformers are able to learn the relationships between text tokens regardless of their order. 

Additionally, transformers are able to learn from large amounts of data, which is important for text detection because there is a lot of variation in the way that text can be presented. 

In this project, we have considered three models Long Short-Term Memory Network (LSTM), DistilBERT, and Robustly Optimized BERT Approach (RoBERTa).

### Deployment

**1. Backend:**  
**Tech Stack:** Python, Flask  

**2. Frontend:**  
**Tech Stack:** React JS

### Conclusion
In this study, we developed a high-quality text corpus of English hate and offensive speech by aggregating four datasets.

To the best of our knowledge, the merged dataset has AI bot - Human interaction text, twitter tweets and other hate/nonoffensive texts. 

We conducted an extensive empirical analysis by taking into consideration three models LSTM, DistilBERT and RoBERTa. 

From results, it is evident that word embeddings extracted by RoBERTa and DistilBERT are best and among both RoBERTa is outperforming. 


[1]:    https://huggingface.co/datasets/tdavidson/hate_speech_offensive "Hugging Face Dataset"
[2]:    https://www.kaggle.com/datasets/andrewmvd/cyberbullying-classification  "Cyber Bullying"
[3]:    https://www.kaggle.com/datasets/arkhoshghalb/twitter-sentiment-analysis-hatred-speech   "Twitter Sentiment Analysis"
[4]:    https://github.com/amandacurry/convabuse    "HateSpeech Data"