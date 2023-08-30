# Project proposal

## 1. Background

Provide the background information about the chosen topic.

- What is it about? 
- Why does it matter? 
- What are your research questions?

## 2. Data 

Describe the datasets you are using to answer your research questions.

- Data sources
- Data size (MB, GB, etc.)
- Data shape (# of rows and # columns)
- What does each row represent?(a patient, a school, a crime, etc.) 
- Data dictionary
  - Columns name
  - Data type
  - Defition
  - Potential values (for categorical valuables, what are the categories?)

## 3. Exploratory Data Analysis (EDA)

- Perform data exploration using Jupyter Notebook
- produce summary statistics of key variables
- Create visualizations
- Find out if the data require cleansing:
  - missing values?
  - duplicate rows? 
- Find out if the data require splitting, merging, pivoting, etc.
- For textual data, you will pre-process (normalize, remove stopwords, tokenize) them before you can analyze them in predictive analysis/machine learning.
- Make sure the resulting dataset need to be "tidy":
  - each row represent one observation (ideally one unique entity/subject).
  - each columm represents one unique property of that entity. 

## 4. Training the machine learning models 

- What models you will be using for predictive analytics?
- How will you train the models (train vs test split, Python packages to be used, and development environments to be used - local, Google CoLab, GitHub CodeSpaces, etc.)
- ow will you measure and compare the performance of the models?

## 5. Application of the trained models

Develop a web app for people to interact with your trained models. Potential tools for web app development:

- Streamlit (recommended)
- Dash
- Flask

6. Conclusion 

7. References 

