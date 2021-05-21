19.05.2021 Status:

Goal:
Main goal of the project is to gather dataset from twitter and implement apriori algorithm.
Here, NSE is used as the key account whose followers list is gathered as Dataset inorder to implement the apriori algorithm and determine or predict the likeliness of the followers who follow a page like NSE.

Sections:
There are 2 sections - Dataset using Twitter API and Implementation of Apriori Algorithm

Packages:
Tweepy - Implemented
Pandas - On process
MatplotLib - Have to implement

Process:

-->  Gather Twitter API using Twitter developer application
-->  Using Twitter API and Tweepy library, gather the required details from a twitter account (Eg: NSE)
-->  Gather the list of followers and collect the list of pages followed by the followers
-->  save it as a csv file.


-->  Implement the apriori algorithm
-->  Create a dataset
-->  Based on minimum support values, generate the list of frequent itemsets(Accounts other than NSE) based on the number of occurences and save them as seperate excel files.


Notes:
Issues faced:
--> We used Apyori package at first
--> Twitter Developer Rights 
--> Rate limtation of Twitter API usage
--> Issue in output -- Have to rectify
