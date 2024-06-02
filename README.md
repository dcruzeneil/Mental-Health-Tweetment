# Understanding Mental Health Conditions by Tweet Analysis

## Abstract
Using an SVM-based approach (for a bag-of-words model), this project aims to analyze symptoms of depression and anxiety by examining tweets. The goal is to provide insights that could aid in delivering appropriate resources to individuals in need, ultimately leading to more effective interventions and improved well-being for communities. For this project, we will be using the <a href="https://www.kaggle.com/datasets/kazanova/sentiment140?datasetId=2477">Kaggle Sentiment140 Dataset</a>, which has tweets annotated with labels (0 = Negative, 2 = Neutral, 4 = Positive). The overall approach for this project would be to bifurcate the dataset into a `training set` and a `validation set`. This would allow testing of how our model would perform on unseen real-world tweets. These criteria will be used to evaluate the success of this project:
<ol>
    <li> Overall Accuracy of the Model on the Validation Data: how does the best model ultimately perform post-training?
    <li> Drawbacks of the "Best" Model: an understanding of the drawbacks of the model. An example of a simple potential pitfall: "I like pears, not apples!" and "I like apples, not pears!". This will include an analysis of what are the <b>false positives</b> and <b>false negatives</b>, and how can we work around those to improve our model.
</ol>

## Data 
<ol>
    <li><a href="https://www.kaggle.com/datasets/kazanova/sentiment140?datasetId=2477">Kaggle Sentiment140 Dataset</a>
</ol>

## Blog Post
A full write-up of this project can be found on my blog: <a href="https://dcruzeneil.github.io/projects/mental-health-analysis/">Analyzing Sentiments from Tweets for Mental Health Support</a>.
