# Natural Language Processing with Deep Learning Final Project

**Group Members:** Stephanie Cabanela and Ayda Nayeb Nazar

**Description:** This repo contains work for a group final project for the Natural Language Processing with Deep Learning course taken in Spring 2023. The goal of this project was to explore and compare NLP approaches to classifying online comments as being toxic towards people with disabilities or not.

## Research Paper

**Title:** "Evaluating Mixed Approaches for Classification of Ableist Toxic Language in Online Comments"

**Abstract:**

Ableism detection in toxic classification is vastly underexplored despite the large global population of people with disabilities who are negatively affected by toxic online discourse. We build deep learning models with CNN and BERT variations to predict ableist toxic comments using a multi-task approach. We first train on ableist comments targeting people with disabilities. We then observe whether training on additional comments targeting other social identity groups (gender, race, sexual orientation, nationality, and religious affiliation) improve ableism detection. We confirm that additionally training on comments targeted at sexual orientation significantly improves ableism detection performance. We compare models by conducting error analysis and try to interpret the models based on the average word length of correct examples, while also learning the limitations of our models potentially due to the challenges unique to ableism.

## How to navigate this repo:

- 266 Final Research Paper - Ableism Detection.pdf - the research paper we co-authored
- notebooks folder - ipython notebooks containing code for training models
- data folder - contains one of the datasets used to evaluate our models. Note that not all data was uploaded to this repo given github's repo size limitations.
- Data_Preparation_Training_Toxigen_Hatemoji.ipynb - contains links to datasets and code for data preparation of our training datasets
- Data_Preparation_Evaluation_Datasets.ipynb - contains links to datasets and code for data preparation of our evaluation datasets
