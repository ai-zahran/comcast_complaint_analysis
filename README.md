# Comcast Complaint Analysis

<a target="_blank" href="https://colab.research.google.com/github/ai-zahran/comcast_complaint_analysis/blob/main/comcast_complaints_data_prep.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

This repo contains code for running text analytics the [Comcast complaints](https://www.kaggle.com/datasets/archaeocharlie/comcastcomplaints) dataset.
This code was created to produce the tables that are used in the [Comcast complaints dashboard](https://public.tableau.com/views/ComcastComplaints/ComcastComplaints?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link).
This project was created for the [2nd Cairo Tableau User Group session](https://usergroups.tableau.com/cairotugmarch2023).

The code performs the following text analytics steps:
1. Topic modeling using [Top2Vec](https://github.com/ddangelov/Top2Vec).
2. Named entity recognition using [Spacy](https://spacy.io/) and [RoBERTa Large NER English](https://huggingface.co/Jean-Baptiste/roberta-large-ner-english).
3. Sentiment analysis using [TextBlob](https://textblob.readthedocs.io/en/dev/), [Vader](https://github.com/cjhutto/vaderSentiment), and the [Amazon Review Sentiment Analysis model](https://huggingface.co/LiYuan/amazon-review-sentiment-analysis).

## How to use
1. Download the dataset and extract it in your working directory.
2. Install the required packages by running `pip install -r requirements.txt` in the terminal.
3. Launch and run the `comcast_complaints_data_prep.ipynb` Jupyter notebook.

# Slides
The slides used for the session can be found [here](https://docs.google.com/presentation/d/180IdvU6q1VGUS3i3W7st9H7VinWsxMR2/edit?usp=sharing&ouid=111548833098119363142&rtpof=true&sd=true).
