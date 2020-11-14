---
layout: page
title: Sentiment Analysis
---
<img align="right" src="/assets/IMDB.jpeg">
# Sentiment Analysis 

In this project, I create a program to analyze <br> the sentiment of movie reviews. I used 40,000 movie reviews labeled positive or negative in sentiment as an initial data set. Then, I used 10,000 movie reviews to test the accuracy of <br>my algorithm.

In order to create this sentiment analyzer, I parsed in 40,000 movie reviews and assigned a positive or negative point value to all words from each review. The words I parsed were added to a map in which the key was the word and the value was the point value of the word. Each word got a positive point for being in a positive review and a negative point for being in a negative  review. Next, I removed all neutral stop words from the map in order to get a more accurate measurement of sentiment. This gave me a map of emotional words and a point value for each word.

In order to test the algorithm, I took 10,000 movie reviews and parsed them word for word. Then, using the map of word values, I added up the point values for each word in the review. This resulted in each review having a total review score of being either positive or negative. I used this score to assign each review a sentiment. I compared the sentiment that I assigned to the review to its actual sentiment in order to get an accuracy score. This algorithm resulted in an accuracy of 68.61%.

In this project, I also implemented a <a href="https://github.com/SMUCSE2341/20f-sent-an-kkleongsmu/blob/master/DSString.h">custom string wrapper </a>class.

<a href="https://github.com/CS1342-Spring2020/program5-kkleongsmu">*Click here for the full Github Repository*</a>

<font size="1"><a href="https://www.imdb.com/pressroom/brand-guidelines/">Image Source</a></font>