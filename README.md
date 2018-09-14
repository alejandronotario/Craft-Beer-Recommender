# Craft Beer Recommender

FMP Alexandra Baron & Alejandro Notario

Data Science Master. KSchool 4th Edition

<br>
<hr>

## Overview:

The main idea of this project is to develope a recommender engine to help craft beer sellers to recommend beers to their customers and therefore to sell more stuff. It has been tried to make web scraping asking for API's ay some websites as "Ratebeer", "Beeradvocate", but it was slow to build an important dataset with queries limitations so eventually it was got a .txt file from Beeradvocate from a Stanford University website with lots of records. From this:

## Prerequisites
- Python 2.7
- Libraries:

## Links and sources


## Folders:

- Data: Obtaining and Scrubbing data 
- Recommnder Engine: Building recommender models

## Steps:

__Data building and cleansing__

This work can be found at Data folder. It has been got a final dataframe from a 2 columns .txt file to use testing code deceloping the recommender engines included in this repository, as well as study data structure and analyze it. Tasks and steps are described in a README included in this Data folder as well as the instructions to run the notebooks inside.  

__Developing recommender engines__

It has been thought to consult different resources to get knowledege and start to program. For this reason, the structure of the Recommender Engine Folder has different ways to approach this target. Notebooks topics are decribe in README included in this Recommender Engine Folder.
Overall it has been taken ratings as the feature which it has been built the engines relating them with users, beers and syles.
_The project has been programmed in Python using Jupyter Notebooks_
_The most important programming steps are explained in the notebooks_

__Conclusions__

- The raw data was huge but it seems there is not enought related fields to get a reliable recommender engine. This is becasue it is missing common ratings between different users, it means more ratings, more users, and more beers rated by users, there are lots of different beers...It is predictable it is going to improve becasuse of obtaining more and more data by beer ratings websites as well as several websites like Amazon, Alibaba, etc.
- Anyway, the models work, but next target is to improve reliability.


__Pending tasks__

- It has been wanted to program NLP to use the text review column which contains users comments to transform them in numerical rating code and use it in some model.

- It has been wanted to make a webservice application using either Flask or Werkzeug to visualize the drop down lists of the 3 engines it have been made which have this application and show the prediction results.

- Maybe an improvement would be to segment the dataset by styles to make recommender engines only for the most popular/rated styles, as well as iterating over other structures.

- All of them are a matter of time.

