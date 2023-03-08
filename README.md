# Project Description
This project consists of three parts 
> A, B and C each focusing on a different aspect of machine learning

## Part A <br/>
In Part A, my task was to examine the "Workers' Productivity Data" dataset and create a multiclass classification model that could predict low, medium, and high productivity. My primary objective was to exhibit that the model could attain an accuracy rate of no less than 60%. This involved performing data analysis and visualization, carrying out data cleaning and feature selection, building and training the model, and evaluating and validating its performance.

Dataset<br/>
| date |   | quarter | department | day | team | targeted_productivity | smv | wip | over_time | incentive | idle_time | idle_man | no_of_style_change | no_of_workers | actual_productivity | productivity |
|------|---|---------|------------|-----|------|-----------------------|-----|-----|-----------|-----------|-----------|----------|--------------------|---------------|---------------------|--------------|

| Attribute | Description |
| --- | --- |
| date | Date in MM-DD-YYYY |
| day | Day of the week |
| quarter | A month was divided into four quarters |
| department | Associated department with the instance |
| team | Associated team number |
| targeted_productivity | Targeted productivity set by the Authority for each team for each day |
| smv | Standard Minute Value: the allocated time for a task |
| wip | Work in Progress |
| over_time | Represents the amount of overtime by each team in minutes |
| incentive | Represents the amount of financial incentive (in BDT) that enables or motivates a particular course of action |
| idle_time | The amount of time when production was interrupted due to several reasons |
| idle_men | The number of workers who were idle due to production interruption |
| no_of_style_change | Number of changes in style |
| no_of_workers | Number of workers |
| actual_productivity | The actual % of productivity that was delivered by the workers, ranging from 0-1 |


## Part B <br/>
In Part B, I sourced relevant images to develop a Convolutional Neural Network (CNN) model capable of recognizing at least four types of musical instruments: Guitar, Piano, Drum, and Violin. My aim was to train the model to achieve an accuracy rate of no less than 70%. I showcased the model training, evaluation process, and application by incorporating a self-source dataset.

This included utilizing an Image Classification API Service with the trained model to predict the class of musical instruments. The website was capable of predicting the class of an uploaded image or an image link. Additionally, I explored using pre-trained models such as InceptionV3 with Adam and SGD in training image recognition models.

## Part C <br/>
In Part C, I chose two areas from the Singapore Model AI Governance Framework and described how to build a trusted AI system for HDB. The areas I chose were internal governance structures and measures and the level of human involvement in AI decision making. I focused on these two areas and explained how to build a trusted AI system for HDB based on the Singapore Model AI Governance Framework.