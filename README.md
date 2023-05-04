# Spooky-Author-Identification
#### To identify horror authors from their writings

## **Description**
The objective of the [Spooky Author Identification](https://www.kaggle.com/competitions/spooky-author-identification/overview) Kaggle competition was to build a machine learning model that could accurately identify the author of a given piece of text as one of three authors: **Edgar Allan Poe, Mary Shelley, or HP Lovecraft**. The competition provided a dataset of 19th-century English texts from these authors, and participants were asked to build a model that could accurately classify new, unseen texts from the same authors.


### **Data Set**

The [Dataset](https://www.kaggle.com/competitions/spooky-author-identification/data) consists of a training set with 19,579 text passages, and a test set with 8,392 text passages.
Each text passage in the dataset is labeled with the author's name, and the goal of the competition was to build a machine learning model that could accurately classify new, unseen texts from the same authors. The text passages vary in length, with some containing just a few sentences and others containing several paragraphs.

**Data fields**
- `id` - a unique identifier for each sentence
- `text` - some text written by one of the authors
- `author` - the author of the sentence (EAP: Edgar Allan Poe, HPL: HP Lovecraft; MWS: Mary Wollstonecraft Shelley)

**In this notebook, To predict the author of excerpts from horror stories by Edgar Allan Poe, Mary Shelley, and HP Lovecraft. This kernel will be my attempt on topic modelling and creating a multiclass classifier. I will be covering different feature extraction techniques- handcrafted and using tf-idf etc, and used Markov Model Based Features finally done with Machine learning model.**

![spooky2](https://user-images.githubusercontent.com/109660074/236336643-88a97bdd-f56a-47c4-bada-4c0fc6fd7802.jpg)
