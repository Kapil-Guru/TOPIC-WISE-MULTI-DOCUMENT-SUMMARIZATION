# TOPIC-WISE-MULTI-DOCUMENT-SUMMARIZATION

In this project, we developed a method for performing topic wise summarization on multiple documents. 
This technique identifies and produces the summary of important details and information on each available topic present in different source documents. 
The idea is to summarize multiple text documents by clustering their contents based on latent topics produced using topic modeling techniques and by generating extractive summaries for each of the identified text clusters. 
All extractive sub-summaries are later combined to generate a summary for each topic in the source documents. 

The dataset utilized for our approach is public comments on federal regulations. 
This is less used and more challenging than more commonly used CNN news dataset for text summarization. 
The well-known news datasets present their most important information in the first few lines of their source texts, which make their summarization a lesser challenging task when compared to summarizing the federal regulation comments dataset. 
Contrary to these news datasets, the documents in our dataset are written using a generalized approach, have lesser abstraction and higher compression ratio, thus proposing a greater challenge to generate summaries. 

INPUT: Source Text Documents
OUTPUT: Topic-wise summaries

Files & Folders description:

Dataset Visualization ---> This folder contains graphs to get insights into the dataset documents

Evaluation ---> This folder contains Rogue score tables and graphs as a result of evaluating our algorithm

Results ---> This folder contains final summary results and intermediate results in csv format

Project Documentation.pdf ---> This file contains comprehensize information on the methodology involved 
