# Proposal Requirements

You project proposal should contain the following sections. 
You will start with a rough draft and update it with more details. 
It will eventually become your final report.

Your proposal will contain the following sections:

## 1. Background

Provide the background information about the chosen topic. 

- What is it about? 
- Why does it matter? 
- What are your research questions?

## 2 Data

Describe the datasets you are using to answer your research questions.

- Data sources
- Number of rows
- What does each row represent?(a patient, a school, a crime, etc.) 
- The Size of the datasets (MB or GB)
- Data dictionary (columns names, types, and defitions)
- Which column/variable will be your target/label?
- Which columns will be your features for predicting your target?

## 3. Preliminary Data Exploration

- Perform basic data exploration using Jupyter Notebook.
- Produce summary statistics of key variables
- Create visualizations (I recommend using Plotly)
- Check the quality of the datasets (missing values? duplicate rows?)
- Find out if the datasets require cleansing, splitting, merging, pivoting, etc.
- For textual data, you will need to pre-process them (normalize, remove stopwords, tokenize) before you can use them in machine learning.
- Make sure the resulting dataset are "tidy" - each row represent one unique entity. each columm represents one unique property of an entity. 

## 4. Training ML Models 

- What models you will be using for predictive analytics?
- How will you train the models?
  - Train vs test split (80/20, 70/30, etc.)
  - Python packages to be used (scikit-learn, NLTK, spaCy, etc.)
  - The development environments (your laptop, Google CoLab, GitHub CodeSpaces, etc.)
- How will you measure and compare the performance of the models?

## 5. Applying the trained models

Develop a web app for people to interact with your chosen trained model using Python web framework. THe following list some frameworks.
I recommend using Streamlit.

- Streamlit
- Dash
- Flask
  
# 6. Summary/Conclusions

- Summarize what you have done
- Limitations & future research directions
- Lessons learned
  
## 7. References 
