# FAKE NEWS DETECTOR
Anna Nguyen, Aiesha Ayub, Aidan Murphy, Jialene Westcott

## Dataset: 
The data is downloaded from Kaggle at https://www.kaggle.com/datasets/bhavikjikadara/fake-news-detection/data and compressed as `fake-news-detection.zip`, containing 2 files: <br /> 
`true.csv`: real news data<br /> 
`fake.csv`: fake news data

## Project goal
The project aims to answer the following questions: 
1. Where do people mostly receive wrong information? 
2. What are the possible signs/words that fake news has?


## Methods
Models used in the training and testing process: <br/>
* Transformers
* Multi Layers Perceptron (MLP)
* Support Vector Machine (SVM)
* Naive Bayes

## Results
The most potential model for our detector is Transformers with a training accuracy of 99.577%, followed by MLP with 99.22%, SVM with 98.57% and Naive Bayes with 94.35%. Even with a high accuracy, Transformers required a big amount of time to train the data. It’s also consuming more training time for MLP than SVM and Naive Bayes. Although SVM was only working on identifying the word patterns, it did a great job producing a high accuracy in a short amount of time, making it the most potential model among the other ones.
