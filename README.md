# Starbucks Capstone Project

# Table of Contents
1. Installation
2. Project Motivation
3. File Descriptions
4. Results
5. Licensing, Authors, and Acknowledgements

# Installation
There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

The list of libraries used in the jupyter notebook are:

* pandas
* numpy
* sklearn
* matplotlib
* seaborn
* datetime

# Project Motivation
For this project, I was interestested in using the data provided by Starbucks to build a ML model that classifies persons wether will respond to an offer based on characteristics as Gender, Time_since_member, Income and Age aiming the goal to send offers efficiently.

# File Descriptions
There are 5 files in the github repository
There are 3 jason files with the raw data. 
The Starbucks_Capstone_Project.ipnyb is a notebook that document and executes the following steps:
* Upload the starbucks information of consumer demographics and transactions during a period of time, with the offers sent clients.
* Explored and visualize the Data
* Apply a series of preprocessing steps for cleaning and getting finally a user-matrix for the ML model.
* Execute a Classification model with random forest for obtaining the users influenced by the offers based on their demographics.
* Refine our model doing GridSearchCV for finding the best parameters.
A Readme.md file, which is the one you are reading in this moment.
Comments were used to assist in walking through the thought process for individual steps.

# Results

* The results obtained in the initial and adjusted model are satisfactory (greater than 60%). In most of the refined models, F-scores are greater than 70%, which shows its high predictive capacity in relation to the initial model. Additionally, the optimized parameters of GridSearchCV found are explaining in a better way the behavior of the costumers.

* Regarding the Features Scores, we identified that the most important variable is “Days since member”, which shows the loyalty of the oldest clients in consuming products. In the other hand, income and age are variables that affect the result but not as much as “Days since member”. The gender variable seems to have no impact in the results.

Read blog post at: https://davidzucchet.medium.com/predicting-the-responsiveness-to-offers-in-starbucks-clients-a512e8e1c123

# Licensing, Authors, Acknowledgements
Must give credit to Starbucks for the data and Udacity for the learning path in the DataScientist Course and some of the code that I reused. Otherwise, feel free to use the code here as you would like!




