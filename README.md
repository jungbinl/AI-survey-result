# AI Survey Analyzing project

## introduction
Using NLP method, analysis the survey result

## Objective

* Basic visualization : show the survey result simply
* Analysis : using word frequency, bigram, sentiment analysis, find the pattern inside the answer
* Machine Learing : using LDA method, find the theme each answer 

## Tech Stack
* Python: Used for automation and pipeline management, specifically for Microsoft auto-scheduling and seamless database updates.
* nltk, pandas, numpy, seaborn, matplotlib, skit learn, OpenAI, os, re

## Project structure
```text
├── Parent Survey.xlxs
├── AI_survey_student.xlxs
├── AI_survey_analysis_student.ipynb
├── AI_survey_analysis_parent.ipynb
└── README.md       # Project documentation and overview
```

## Analysis Method

* Basic bar, pie graph : show the survey result simple

* Word Frequency: Identifies the most commonly used words to capture the primary focus of each speech.

* Sentiment Analysis: Quantifies the overall positive or negative tone of the speeches to track emotional shifts over historical eras.

* Bigram : relationship between two noun word


## Machine Learning Method

Utilizes unsupervised learning algorithms to automatically discover hidden themes and topics.

* LDA (Latent Dirichlet Allocation): A generative statistical model that allows sets of observations to be explained by unobserved groups (topics). It identifies which topics dominate each president's tenure.
