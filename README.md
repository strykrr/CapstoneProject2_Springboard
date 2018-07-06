# CapstoneProject2_Springboard
## Portfolio Project 
### Problem Statement

Classify articles into meaningful categories irrespective of any Discipline to fulfill business needs or improve the User Experince    while browsing content of the files online.

### clients for Topic Modeling

Digitization of Podcasts has lead to multitude of archive collections Online, Users would like to play the podcasts of their choice. What if there is a way Podcasts are Organized better to thoroughly enjoy without any hassle of going through the entire list of episodes.By applying various Machine Learning techniques Podcasts can be arranged in the order of relevance based on the coverage of different Topics,thus giving us understanding of how similar and dissimilar are the podcasts.

### Data Acquisition

Econtalk is a famous podcast listened by people across the world, classification of these Podcasts using Topic Modeling on the transcripts creates an opportunity for the listeners to tune in with their interests. Podcasts listeners can be recommended and save lot of time in exploring , caterring to their needs and customizing the articles based on their Interests.

This is a link to the Archive of Econtalk Podcasts. Web scraping of the transcripts into text format provides an opportunity for Clustering of Topics. www.econlib.org/econtalk-favorite-by-date

**Webscraping** - Webscraping is a wonderful technique to extract content from websites and create data for Topic Modeling yourself.Beautiful Soup is a Python package used for web scraping to parse HTML and XML documents.It creates a parse tree that can be used to extract data from HTML.
                  
  EconTalk hosts archives of Podcasts dating back until 2006 which aggregate close to 500 documents. Beautiful Soup enables to parse the HTML content and extract all the URL's of the podcasts.Once the URL's are extracted ,web content of each podcast can extracted by navigating to appropriate url via Beautiful Soup and further split each documennt to have more than thousand documents for Topic Modeling.

**DataWrangling**- Gensim provides package to Preprocess the Text content before applying the machine Learning Algorithms.
             
### List other potential data sets you could use
All the Data required for Topic Modeling is extracted from the Econtalk website

### Explain your initial findings**
Identify similarity and dissimilarity of Podcasts from huge collection of archives in Econtalk based on the Semantic Structure of Topics covered in the Text documents.

### Share the Capstone Project 2 code and milestone report related to Github repository**

