# Understanding Mental Health conditions by Tweet Analysis

## Abstract
Using a deep learning approach (amongst other machine learning techniques), this project aims to analyze symptoms of depression and anxiety by examining tweets. The goal is to provide insights that could possibly aid in delivering appropriate resources to individuals in need, ultimately leading to more effective interventions and improved well-being for communities. For the purpose of this project we will be using the <a href="https://www.kaggle.com/datasets/kazanova/sentiment140?datasetId=2477">Kaggle Sentiment140 Dataset</a>, which has tweets annotated with labels (0 = Negative, 2 = Neutral, 4 = Positive). The exact mechanism (in terms of the algorithmic approach adopted) is not finalized, however, the overall approach for this project would be to bifucrate the dataset into a training-set and a validation-set. This would allow testing how our model would perform on unseen real-world tweets. By testing different machine learning models, this project aims to understand the nuances of what might lead one to perform better than the other, and if so, exploring any situations where one might be better than the other. To evaluate the success of my project, I have 3 main criteria and 1 additional criterion:
<ol>
    <li> Overall Accuracy of the "Best" Model on the Validation Data: how does the best model ultimately perform post-training?
    <li> Analysis of the Models: a nuanced understanding of why certain models perform better than others?
    <li> Drawbacks of the "Best" Model: an understanding of the drawbacks of the model. An example of a simple potential pitfall we discussed in class was, "I like pears, not apples!" and "I like apples, not pears!"  
    <li> Additional: creating a simple web-app where users can type in a tweet (or a sentence), and get a result about the sentiment (which links back to our original goal of analyzing symptoms of depression and anxiety) of the tweet 
</ol>

## Motivation and Question
As mentioned before, this project aims to use the Kaggle Sentiment140 Dataset, which contains tweets which are annotated with a score from 0-4 (0 = Negative, 2 = Neutral, and 4 = Positive). Since language is what we used to describe what we are feeling, for a human it is a way to tell how someone is feeling. However, this project aims to use machine learning to see if we can actually make good predictions based on unseen data. <br>For this purpose, the scientific question that this project will try to answer can be summarized as: <i><u>Given a tweet (or a statement for generality) can we predict the mood (happy, neutral, sad) of the author?</u></i> Therefore, the type of decisions the model would be making would involve: discerning "happy" tweets from "sad" tweets, trying to discern "sarcasm" (tweets which are not "sad" but are "sarcastic") from actually "sad" tweets, and so on. Additionally, an analysis of what are the <b>false positives</b> and <b>false negatives</b>, and how can we work around those to improve our model.


## Planned Deliverables
For this project, I have 3 planned deliverables:
<ol>
    <li> Python Package: this will contain the code for our machine learning models, and will also include the functions which we will use to calculate our loss and accuracy. This will also contain documentation which explains the important functions. 
    <li> Jupyter Notebook + Blog Post: similar to our previous blog posts, I aim to create a blog post out of my Jupyter Notebook. This will illustrate the use of the package and will be used to perform experiments around the model that we have trained. 
    <li> Web-App: a simple web-app which will implement our model for sentiment (depression and anxiety) analysis, and that has an easy interface that users can interact with. The users simply need to put in a tweet (or, a sentence) and they will get a result regarding what the model classifies their tweet as.
</ol>

Evaluating the effectiveness: 
<ul>
    <li> Partial Success: achieving a relatively high score on the validation data (for our trained model) and implementing the package in a Blog Post (Jupyter Notebook)  
    <li> Full Success: achieving a pretty high score on the validation data (for our trained model), implementing the package in a Blog Post (Jupyter Notebook), and creating a simple web-app which implements this trained model 
</ul>

## Resources Required 
For the purpose of this project, I do not require any special resources:
<ol>
    <li> Data: <a href="https://www.kaggle.com/datasets/kazanova/sentiment140?datasetId=2477">Kaggle Sentiment140 Dataset</a>
</ol>

## What You Will Learn
As mentioned in my reflective goal, I am interested in exploring the <i>Implementation</i> and <i>Experimentation</i> side of machine learning. This project will allow me to work on a real-life dataset and work on a project with a real-life impact, thereby, allowing me to adhere to these learning goals. Furthermore, this project will allow me to develop the following skills: 
<ol>
    <li> Natural Language Processing
    <li> Deep Learning
    <li> Git and Version Control
    <li> Django: which I will use to develop the web-app 
</ol>

## Risk Statement 
This project could run into the following risk: 
<ol>
    <li> Nuances of Language that the Model might not be able to accomdate: sarcasm and wordplay
    <li> Potential Lack of Computational Power: there might be a potential lack of computational power, especially, if there is a Document-Term Matrix involved 
</ol>

## Ethics Statement
<ol>
    <li> Potential Benefit: people who are dealing with mental health issues (depression and anxiety)
    <li> Excluded from Benefit: people who do not write on the internet (Twitter) in languages other than English. This is also due to a lack of enough data (dataset) in other languages, and also a lack of NLP techniques which are focussed on languages other than English
    <li> World a Better Place: Yes, I feel that the world might become a better place because of this project! This is based on the following assumptions:
        <ul>
            <li> Depression and Anxiety symptoms (sentiments) are predictable using the textual language that a person uses!
            <li> The world is a better place when you can intervene and provide adequate resources to people who are dealing with certain issues!
        </ul>
</ol>
