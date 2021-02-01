# Twitter_Sentiment_Analysis
[Twitter](https://twitter.com/) is an American microblogging and social networking service on which users post and interact with messages known as "tweets". Registered users can post, like and retweet tweets, but unregistered users can only read them
The dataset belongs to Standford University, Since I cannot find the original source but research papers, I use the dataset that public on [Kaggle](https://www.kaggle.com/kazanova/sentiment140)

![Twitter](https://user-images.githubusercontent.com/63126292/106425944-51e07280-642a-11eb-888d-ad13efa902c3.jpg)

## 1. What are the target of this project?
* Detect the Positive or Negative tweets

## 2. My solution. 
* Understanding the dataset by applying EDA and descriptive analysis
* Applying vectorized tranformation to convert word to vector
* Utilized Machin learning to predict Positive and Negative tweets

## 3. Outcome
* From the dataset, the amount of positive and negative tweets are almost the same
* Words in Positive Tweets ![download (2)](https://user-images.githubusercontent.com/63126292/106426389-21e59f00-642b-11eb-9a18-75585935121a.png)
* Words in Negative Tweets ![download (3)](https://user-images.githubusercontent.com/63126292/106426363-14c8b000-642b-11eb-905a-149dcbcf0940.png)

* The best vectorized method is TF-IDF, which has the lowest log loss and highest accuracy scores in all machine learning algorithms

[Bernoulli Naive Bayers] ![Screen Shot 2021-02-01 at 1 21 25 AM](https://user-images.githubusercontent.com/63126292/106426829-e7303680-642b-11eb-965d-34d12dd1f973.png)

[Logistic Regression] ![Screen Shot 2021-02-01 at 1 21 14 AM](https://user-images.githubusercontent.com/63126292/106426898-0333d800-642c-11eb-934e-7c19428f314a.png)

* The best machine learning algorithms is Logistic Regression and the second ond is Bernoulli Naive Bayers
[Accuracy] ![download (5)](https://user-images.githubusercontent.com/63126292/106426940-18a90200-642c-11eb-8022-0780b24b60c1.png)

[Log Loss] ![download (4)](https://user-images.githubusercontent.com/63126292/106427012-3a09ee00-642c-11eb-9b91-1a2d6c3cde8c.png)

* For tunning the best parameter sets: 
  ** The best one for Logistic Regression are  ```lr__C: 1.0, lr__penalty: 'l2', lr__solver: 'newton-cg'```
  ** The best one for Bernoulli Naive Bayers are ```nb__alpha: 4, nb__binarize: 0```
  
## 4. Conclusion
* My research is a good practice for understand NLP and predict a model for sentiment analysis
* It is useful for News, Economics, Journalists, Data collectors for predict futre twitters, or other social media platform to predict sentiment.
