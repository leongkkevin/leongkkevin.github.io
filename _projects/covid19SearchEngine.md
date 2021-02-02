---
layout: page
title: COVID-19 Search Engine
permalink: /COVID_Search_Engine/
---
# COVID-19 Search Engine

This project is a culmination of an entire semester's C++ learning. In this project, a partner and I utilized <a href="https://github.com/leongkkevin/covidSearchEngine/tree/master/rapidjson">rapidJSON</a> to parse through 12,000 articles in order to create an inverse file index of words (stored in a <a href="https://github.com/leongkkevin/covidSearchEngine/blob/master/DSTree.h">custom AVL Tree class</a>) and an index of authors (stored in a <a href="https://github.com/leongkkevin/covidSearchEngine/blob/master/DSHashTable.h">custom HashTable class</a>). **This algorithm's speed was ranked in the top 25% of the course's students**.

We created an interface to allow the user to look search both these data structures and find a specific word:

<img align="center" src="/assets/covidSearchMenu.png" style="width:700px;"/>

From this menu, the user can parse through a folder of .json articles, store an already open index into a persistence file, or load a persistence file. Then, they can search through the index with **boolean operators AND, OR, and NOT** to get a specific result. The top 15 articles with the highest query frequency are shown below:

<img align="center" src="/assets/covidSearchResults.png" style="width:700px;"/>

From there, by selecting a certain article number, the tool brings up the title, author(s), publish date, and the first 500 words from both the abstract and the body paragraphs.

<img align="center" src="/assets/covidSearchArticle.png" style="width:700px;"/>

As well as this, the system also can show the top 50 most common words, the average words per article, the total number of words in all articles, and the amount of unique authors. 

<a href="https://github.com/leongkkevin/covidSearchEngine">*Click here for the full Github Repository*</a>

<br>
<a href="{{site.baseurl}}/projectPage.html">*Back to Projects*</a>