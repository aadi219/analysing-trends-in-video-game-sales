# Analysing Trends in Video Game Sales
Performing data analysis on a dataset containing information on video game sales arcross different regions.
## Project Components
### Language Specifications
Data Analysis done using Python Jupyter Notebooks
```
python 3.9.1
```
Libraries and Modules used:
```
pandas 1.4.0
numpy 1.20.1
matplotlib 3.4.2
seaborn 0.11.2
ipython 8.4.0
```
### Data
Dataset taken from Kaggle
The referenced dataset is linked [here](https://www.kaggle.com/datasets/kedokedokedo/vgsales/)
## Project Motivation
As a person with an avid interest in both statistics and video games, this dataset provided an interesting challenge to analyse the market in regions with vastly different cultures and audiences, for an industry I have been following for years.
With the given dataset, I wished to answer the following questions:
* How do the sales in video games across different regions differ and how have they changed over the years?
* Which genre has received the most sales in each region and across the world?
* Which publisher has seen the most success in terms of video games sold in each region and across the world?
* Which platform has witness the most amount of sales for video games sold for it in each region and across the world?
* Can any observations be made which connect the market for the video game industry to its region and to the companies which produce the video games and the platforms?
## Steps Taken during the Data Analysis Process
### Understanding the dataset
The dataset consists of the following columns
* Rank - The ranking of a video game with respect to global sales
* Name - The name of the video game
* Platform - The platform for which the game was released
* Year - The year in which the game was released
* Genre - The genre of the video game
* Publisher - The company which published the video game
* NA_Sales - The amount of copies sold for the video game in North America (in millions)
* EU_Sales - The amount of copies sold for the video game in Europe (in millions)
* JP_Sales - The amount of copies sold for the video game in Japan (in millions)
* Other_Sales - The amount of copies sold for the video game in other regions (in millions)
* Global_Sales - The amount of copies sold for the video game across the world (in millions)
### Loading relevant Libraries and Modules
The Pandas library was used to load and perform operations on the csv dataset
Numpy, Matplotlib and Seaborn were used to represent the data graphically
### Data Cleanup
The dataset included some rows for which the publisher column contained null values. Those rows were hence removed to ensure accurate operations and analysis
### Graphical Representation of Data
The clean data was then grouped and aggregated with respect to the question I wished to answer for that section. The aggregated data was then represented in the form of an appropriate graph.
## Result
The step-by-step process of the data analysis process can be reviewed in the jupyter notebook along with the graphs and answers to the questions I had posed.
## Observations
Some interesting observations can be made when considering the data relevant to the Japanese Region. Nintendo is a Japanese Video Game company which has published games which are consistently the most popular across all regions. Nintendo is also the creator of video-game platforms such as the Wii, DS, NES and SNES which are all amongst the top most popular platforms across all regions. It can also be observed that all of the top 5 publishers for the Japanese Region are Japanese Companies with some of those companies such as Nintendo and Sony also being in the top publishers for other regions as well. However, even though there are multiple Japanese Companies which have dominated the video-game industry for decades, those companies have found their markets within other regions and the popularity of video-games in Japan still severely lacks behind North America and Europe in terms of sales.

