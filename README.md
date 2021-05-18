# WebshopClassification

The goal of this project is to develop a machine learning model, that is able to predict the (non-)existance of a webshop on a specific website based on its text content. As a consequence, multiple German websites have been scraped automatically in advance. Additionally the corresponding labels have been added denoting if the web site is an online shop or not (0 = no shop; 1 = is shop).

## Project Outline:

The project comprises the following steps, which are built on each other:
1) Create the dataset
2) Preprocess the data
3) Build the classifier (Selection, Training, Finetuning, Evaluation, Explanation)
4) Make the prediction

## Data Sources:

The data contains the following files and folders:
* dataset1.csv: Domain name and flag if the web site is an online shop (to be used to training)
* dataset2.csv: Domain names which are unlabelled so far (to be used for predictions)
* Folder „scraped_html“: One file with scraped HTML code of the main page for each of the web sites.

## Tech Stack:

* *BeautifulSoup*
* *NLTK*
* *Regex*
* *Pandas*
* *Numpy*
* *Scikit-learn*
* *Gensim*
* *Matplotlib*
* *LIME*
