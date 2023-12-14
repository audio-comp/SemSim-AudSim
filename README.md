
Dataset of adjective-noun (AN) phrase similarity judgments for the following two tasks:

1) Semantic Similarity
2) Audio Similarity

For each task, the dataset contains 30 adjectives with 15-20 nouns each, and 3,258 adjective-noun pairs. 
We collected human judgements from Amazon Mechanical Turk(AMT) with 15 different subjects per questionnaire totalling 113 annotators and 48,870 annotations for each task
Inter-annotator agreement between the annotators is 0.69 for semantic similarity and 0.67 for audio similarity.


Description of files:

* annotations.csv: file containing the informative fields from the AMT experiment.
  The fields are as follows:
  - id : unique reference for each annotation
	- pair : adjective-noun pair (AN1-AN2) to be annotated	
	- Sem_Sim: Mean semantic similarties scores of 15 annotators
	- Aud_Sim: Mean Audio similarties scores of 15 annotators

* AMT-sample :This folder contains a snapshot of the instructions and pair samples as presented to the annotators for each tasks. 


When using the data set, please cite:

@article{Nazir:etal:2023,
author = {Saba Nazir and Mehrnoosh Sadrzadeh},
title = {How Does an Adjective Sounds like? Improving Audio Phrase Composition using Text Embeddings},
journal = {--},
year = {--},
}

