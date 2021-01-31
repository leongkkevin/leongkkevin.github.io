---
layout: page
title: Auto Indexer
permalink: /autoIndex/
---
# The Auto Indexer

This project takes an input of a formatted text file that includes page numbers and words that exist on that page. The algorithm parses this text and outputs a alphabetically organized index of the words and the pages they appear on. The project also has sub-indexing capabilities in which sub-words can be appended to words and will be shown in the output under the parent word.

![autoIndexExample](/assets/autoExample.png)

In the input above, the integers inside of the less and greater than symbols represent the page number. Indexed phrases are also surrounded by square brackets. Words followed by another word in paranthesis are subwords to the word inside the paranthesis. The output file is formatted alphabetically with subwords listed below the parent words.

In order to index the file, I created a <a href="https://github.com/leongkkevin/autoIndexer/blob/master/WordEntry.h">WordEntry class</a> that holds the word itself, a set of pages the word appears on, and a vector of children words. I parsed through each word in the input file, creating a new WordEntry and adding it to a set. A pointer stored the location of the previous entry and added that word as a child to the word found in paranthesis after.

I also implemented my own custom <a href="https://github.com/leongkkevin/autoIndexer/blob/master/DSString.h">string wrapper class</a> as well as custom, templated <a href="https://github.com/leongkkevin/autoIndexer/blob/master/DSList.h"> doubly linked list</a> and <a href="https://github.com/leongkkevin/autoIndexer/blob/master/DSVector.h">vector</a> classes.

<a href="https://github.com/leongkkevin/autoIndexer">*Click here for the full Github Repository*</a>

<br>
<a href="{{site.baseurl}}/projectPage.html">*Back to Projects*</a>