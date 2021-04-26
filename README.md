# hottest-topics-in-ML
An Original DataCamp Project by Lars Hulstaert.

*Background:* 

As one of the most prestigious yearly events in the machine learning community, the NIPS conference (Neural Information Processing Systems) is a place that a large number of research papers are published each year. Over 50,000 PDF files were automatically downloaded and processed to obtain a dataset on various machine learning techniques. These papers discuss a wide variety of topics in machine learning, from neural networks to optimization methods and many more.

## Given a NIPS papers data set, what are the hottest topics in Machine Learning for these 30 years (1987-2017)? 


**Goal:** 

*Find Hottest Topics in ML*
- Analysis of a NIPS papers data set using LDA and Visualization 


**Dataset:** 
Over 50,000 NIPS papers are stored in datasets/papers.csv. The CSV file contains information on the different NIPS papers that were published from 1987 until 2017. 


*Data File Name:* papers.csv

*Columns:* id, year, title, event_type, pdf_name, abstract, paper_text  

File Located in DataCamp Server


## Steps

- Preparing the data for analysis
- Plotting how machine learning has evolved over time
- Preprocessing the text data
- A word cloud to visualize the preprocessed text data
- Prepare the text for LDA analysis
- Analyzing trends with LDA
- The future of machine learning


## Language 

The programming language: Python 3

The file format: ipynb 
- Any application that can open .ipynb file will be great, but I highly recommend using Google Colab or Ananconda Jupyter Notebook.

The comment and text language: English 

## Packages Installed 
Python packages: pandas and some other ML packages

- The codes include installing packages are already embedded in this notebook. It shouldn't have problem if you run my code step by step. 

## Expected Outcome
The expected outcome should already be displayed in the notebook under the codes, but feel free to test the code on your own.

## Logic Behind
Topic modeling is a method for unsupervised classification of documents, similar to clustering on numeric data, which finds some natural groups of items (topics) even when we’re not sure what we’re looking for.

LDA is one of the most popular topic modeling methods. Each document is made up of various words, and each topic also has various words belonging to it. The aim of LDA is to find topics a document belongs to, based on the words in it. 

  -- A Beginner’s Guide to Latent Dirichlet Allocation(LDA) https://towardsdatascience.com/latent-dirichlet-allocation-lda-9d1cd064ffa2


Other resources related to LDA provided by scikit-learn developers can be found at: https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.LatentDirichletAllocation.html 

## Contributing
Apologize in advance that any pull requests other by the host might be rejected because this is a certified DataCamp Project that reserved by Lars Hulstaert.

Still, welcome to open an issue if you have something want to discuss, or directly contact with me via my email (xxie3@lion.lmu.edu or xiekassie@gmail.com).

### The codes' rights reserved by Lars Hulstaert and Kassie Xie. Other rights all reserved by Lars Hulstaert. 
