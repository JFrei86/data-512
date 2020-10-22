## About the data
The corpus is called the Wikipedia Talk corpus, and it consists of three datasets, two of which are analyzed here. Each dataset contains thousands of online discussion posts made by Wikipedia editors who were discussing how to write and edit Wikipedia articles. Crowdworkers labelled these posts for three kinds of hostile speech: “toxicity”, “aggression”, and “personal attacks”. Many posts in each dataset were labelled by multiple crowdworkers for each type of hostile speech, to improve accuracy. I have provided the "toxicity" and "aggression" datasets which were under analysis.

Overview of the research project that : https://meta.wikimedia.org/wiki/Research:Detox (Links to an external site.) 
Dataset description and schemas: https://meta.wikimedia.org/wiki/Research:Detox/Data_Release (Links to an external site.) 
Overview of Google’s Conversation AI project: https://conversationai.github.io/ (Links to an external site.) 

## Deliverables in this assignment

- `hcds-a2-data-bias.ipynb` A notebook containing all of the code used for exploring the dataset.

## Data files in this assignment

- `toxicity/toxicity_annotated_comments.tsv`
- `toxicity/toxicity_annotated_comments_sample.tsv`
- `toxicity/toxicity_annotations.tsv`
- `toxicity/toxicity_annocations_sample.tsv`
- `toxicity/toxicity_worker_demographics.tsv`
- `aggression/aggression_annotated_comments.tsv`
- `aggression/aggression_annotated_comments_sample.tsv`
- `aggression/aggression_annotations.tsv`
- `aggression/aggression_annocations_sample.tsv`
- `aggression/aggression_worker_demographics.tsv`

## Questions under analysis

1. What are top 5 comments with the least agreement for toxicity and aggression?
   (Which comments have the highest variance in annotation?)
2. Do gender, education, and English as a first language, play a factor in labelling behavior for aggression and toxicity?
   (Is the mean different between genders, between education levels, and different first languages?)

## Motivation

The hypothesis for this exploration is that annotator gender, education, and first language each play a role in labelling behavior for aggresion and toxicity. I also hypothesize the comments with the least agreement for toxicity and aggression contain words and phrases that are not overtly aggressive, or perhaps do not use formal grammatical structure.
