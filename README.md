# twitter_sentiments_analysis_racism
Identifying the degree of profanity in the tweets (Racism checking in tweets)

## Problem Statement
Imagine there is a file full of Twitter tweets by various users and you are provided a set of words that indicates racial slurs. 
Write a program that can indicate the degree of profanity for each sentence in the file. Write in any programming language (preferably in Python) - make any assumptions, but remember to state them. Please place the code in GitHub with proper documentation and share.


## My Approach
<hr>
My approach for this problem statement was simple, I break the overall Problem in 3 sub parts, and hence proposed the solution.

<strong>Sub parts are as follow:</strong>
1.	Understand the Problem statement clearly 
2.	Clean the data and make the provided dataset in best possible format
3.	Solve the Objectives

I spend good time on looking through the problem statement and finding the core logic behind it and hence took step to solve it.

After understanding the problem statement, I went for reading few of the articles to get to know their approach for the similar problems.

Reading and researching about the topic for a while, I get the vision of how I would be dealing with the problem and the moved to next part.

Making my dataset in best possible format.

For me, I am having quite a bit of experience with pandas data frame, So I converted the dataset into pandas data frame and then started with the implementation of my ideology.


For me, the ideology was:

<strong>Find the degree of profanity for each tweets using tokenization</strong> 

For this, I created a new column with name “Clean tweets” where I removed unnecessary, symbols, texts, emojis and other elements that was of no use for this problem from the tweets.

After that, I used this clean tweet for tokenization where I break the sentence into single words.
Using these words, I made entity which further I put in counter and solved the problem.

I spend time in learning about sentiments analysis and get to know about "SentimentIntensityAnalyzer". And how I can implement using NLTK kit.

After understanding, I applied it over the clean tweets, which gives me the  result weather the sentiments were, racial slurs or not.
After that I done with formatting that leads to solution of the problem statement.

Technique I use and the reason why you I chosen it.
Here are the steps in bullet points:
1.	Looking through Data description in Detail
3.	Cleaning tweets with NLP

> *	Finding if the text has:
>	* URL Link
>	* Hashtags
>	* Emojis
>	* Word less than 2 character
>	*  And others...

4.	Finding the racial slurs in the tweets
5.	Data visualizing



