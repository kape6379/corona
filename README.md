# **NLP with Coronavirus Tweets using Long Short-Term Memory Networks**
#### Kate Pendavinji
#### **Repository Link:** [Project Repo](https://github.com/kape6379/corona.git)

### **Gather Data:**

My data was gathered from [kaggle](https://www.kaggle.com/datasets/datatattle/covid-19-nlp-text-classification?select=Corona_NLP_train.csv). It pertains to twitter data regarding tweets related to the Coronavirus Pandemic. 

The data is split up into testing and training data. They will be read from a CSV which I will go on to explore further in my data exploration section. 


### **Identify a Deep Learning Problem:**
The deep learning problem I seek to answer is to automate the classification of pandemic related tweets based on the sentiment of the tweet (positive, negative, neutral, etc.). In order to do this I will be using _natural language processing_ on the tweets similarly to the week 4 project and seeing if long short-term memory networks can give us accurate predictions of the sentiments of our data. I will then attempt to see how using an SGD optimizer affects the accuracy of our training and test accuracies and losses. 

_For entire code please look at corona-2.ipynb, for data open corona file and observe test and train datasets._
