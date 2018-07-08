# CapstoneProject2_Springboard
## Portfolio Project 
### Problem Statement

Classify articles into meaningful categories irrespective of any Discipline to fulfill business needs or improve the User Experince    while browsing content of the files online.

### Approach
The Following Steps were followed for Topic Modeling
* Web Scraping  - Extraction of Text Documents from the Archives of EconTalks Podcasts using Beautiful Soup 
* Data Precoseesing - Utilised the Gensim package for data wrangling and clieaning of Text Documents for further analsysis dow the line.
* Topic Modeling - Application of various Algorithms such as LDA and Mallet from Gensim libraries tp find the semantic structure of Doucments and understand the Topic Distribution.

### Results
LDA Mallet performs better than LDA model with a Coherence score of .5632 when the number of topics is 20 with 1000 Iterations. Mallet has good  association of terms with Topics which is more sensible and comprehesible with humans.

### Repository Structure
* WebScraping_Titles&Links.ipynb - Extraction of  all the html links to the archives of Podcasts in EconTalk
* econtalk.json - Distionary of all the Podcast links
* CreateDocuments.ipynb -   Creation of Documents from the html links.
* Topic_Modeling.ipynb - Code implementing Data Preprocessing and Topic Modeling to find the semantic structure of Documents.
* Capstone2_Report.pdf - Report capturing the implementation and analysis of Topic Modeling

