# Fake News Detection Using Logistic Regression
<h1>OBJECTIVE:</h1>
The main objective is to detect the fake news, which is a classic text classification problem with a straight forward proposition. It is needed to build a model that can differentiate between “Real” news and “Fake” news.
<h1>REQUIREMENTS:</h1>
<ul><li>Python</li>
<li>Numpy</li>
<li>Pandas</li>
<li>Itertools</li>
<li>Stemming tools</li>
<li>Sklearn</li></ul>
<h1>Data:</h1>
<p>I have shared my training data in the below link.</p>
https://drive.google.com/file/d/1RlIfucizysBxCs0w3hohQWgsWaGd21iL/view?usp=sharing
<h1>Processed Method:</h1>
<p>First,I have imported the required modules to the colab file.Then, I downloaded the stopwords from nltk library.I have inserted the dataset to a variable using pandas.read_csv() function</p>
<p>Next, I have applied the Data preprocessing methods to the training dataset.I have filled all the null values present in the dataset with blank space''.</p>
<p>I have created a column named 'content'  in the dataframe which consists of both 'author' and 'title' column values.</p>
<p>Next, I have seperated the features and label and assigned them to variables.</p>
<p>Using PorterStemmer() class, I created a function which will return all the text data consisting of only root words.Then, lets take the feature as column 'content' and apply the vectorizer function to convert text data into numerical data.</p>
<p>Now, lets split the training data amd testing data using train_test_split() function.Then, I used Logistic Regression to create the model.I finally achieved accuracy score of the training data  as 96.9% and for testing data as 95.2%</p>
<h1>Refrences:</h1>
<ul>
<li>https://www.youtube.com/watch?v=nacLBdyG6jE</li>
<li>https://www.pantechsolutions.net/fake-news-detection-using-machine-learning</li>
</ul>
