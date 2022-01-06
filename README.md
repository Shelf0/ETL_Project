# Project_2
Second Coding Project

Buit a database that contains information on different countries including the capitals as well as the average exports of each country 

EXTRACT:

I first extracted data on how much each country has exported (in USD) by searching the internet. I came across a wikipedia page that listed those things out and I copied
the table from wikipedia. From there I brought that data into excel and I simply created a CSV of that exact table for use in pandas. 

Besides that I called upon an API from BigDataCloud that listed out country data, including the capitals of the countries. After playing around with it and other API's in order to extract the JSON data, 
I came across an actual JSON file on Git Hub that contained the capitals, located here: https://github.com/icyrockcom/country-capitals/blob/master/data/country-list-with-ids.json

From there I took that JSON file as well as the CSV file I created and saved it into my github repository


TRANSFORM 

First, I dealt with the CSV file. I imported the file from my github repository into a Jupyter notebook where I ran Pandas. I transformed my data by getting rid of unnecessary data, re organizing
the data to be in alphabetica order, setting the index of the file to be in akphabetical order so I ended up with Countries as the index in an akphabetical order. 

I then repeated this with the dataframe that contained the countries capitals. 

LOAD

lastly, I opened postgres SQL and created a database. I then opened my database and navigated within PGAdmin to where my expoted files lived. I then used SQL queries such as SELECT & JOIN in order to bring
some of the data into the database. 
