---
title: Sentiment Analysis
layout: PostLayout
date: '2023-01-30'
colors: colors-c
author: content/data/team/hilary-ouse.json
excerpt: >-
  I evaluate the customer sentiment analysis using the Amazon Food dataset in a
  Jupyter notebook with the help of the Python Visualization Package and natural
  language processing(NLP)........ Currently working on it!!!!!!!!!!
featuredImage:
  type: ImageBlock
  url: /images/0_Akql8a3a_INHYMIa.gif
media:
  type: ImageBlock
  url: /images/0_Akql8a3a_INHYMIa.gif
bottomSections:
  - elementId: ''
    variant: variant-d
    colors: colors-d
    title: Read next
    showDate: true
    showAuthor: false
    showExcerpt: true
    recentCount: 3
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-56
          - pr-4
          - pl-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
    type: RecentPostsSection
  - type: DividerSection
    colors: colors-d
    styles:
      self:
        width: wide
        padding:
          - pt-4
          - pb-4
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
addTitleSuffix: true
---
### \*\* Currently Working on it.......................\*\*

## **Introduction**

Sentiment analysis is used to analyze customer reactions to products. Now you have learned the basics of the working purpose of nltk used in NLP projects. In this project there are so many steps to complete the whole project.

### **Steps**

#### Step 1:- Read in Data and NLTK Basics

In this step, we was first import packages like Pandas, Numpy, Matplotlip, Seaborn, NLTK in Python. Then use Pandas to read the data, then Matplotlib to read Quick EDA, then starts Basic from NLTK.

#### Step 2:- VADER Seniment Scoring

I will use NLTK's `SentimentIntensityAnalyzer` to get the neg/neu/pos scores of the text.

*   This uses a "bag of words" approach:

    1.  Stop words are removed

    2.  each word is scored and combined to a total score.

And at the end of this step I will Plot the VADER result.

#### Step 3:- Roberta Pretrained Model

*   Stop words are removed

*   each word is scored and combined to a total score.

<!---->

*   Use a model trained of a large corpus of data.

*   Transformer model accounts for the words but also the context related to other words.

And at last Compare Scores between models.

#### Step 4:- Combine and compare

#### Step 5:- Review Examples:

*   Positive 1-Star and Negative 5-Star Reviews

Lets look at some examples where the model scoring and review score differ the most.

#### Step 6:- The Transformers Pipeline

Quick & easy way to run sentiment predictions.\<!---->

