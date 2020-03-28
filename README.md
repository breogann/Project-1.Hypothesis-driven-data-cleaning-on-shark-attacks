<p align="center">
  <img width="1000" height="300" src="https://github.com/breogann/hipotheses-driven-data-cleaning-on-sharks-attacks/blob/master/Images/cover.png" alt="Data cleaning">
</p>

# Hypotheses driven data cleaning on shark attacks

Project on data wrangling. In this project we use a dataset on shark attacks from Kaggle (https://www.kaggle.com/teajay/global-shark-attacks) in order to hypothesize and obtain information.

## Data 📊 ##

The dataset is formed by over 5.990 worldwide registered cases of shark attacks, including information about: location, activity, age, sex, fatality, reference number and others. 


## Hypotheses 🔬 ##

- Hypothesis # 1: Spear-fishers are more frequently attacked than peolpe doing any other activity.

- Hypothesis # 2: Women are less attacked by sharks than men.

- Hypothesis # 3: The more recent the event, the higher the records are.


*Formulation of hypotheses drives the obtention and filtering of data. The performed statistical analysis is more descriptive than inferential (and so it would be needed to apply variance statistical test in order to test the hypotheses).

## Data processing 🛠 ## 

- Elimination of redundant information (dropping unnecessary columns)
- Elimination of incomplete or faulty registers
- Standarization (of column names and data) and merging of columns
- Cluttering conditions (eg.: spear-fishers & fatality)
- Comparisons of total and relative events
- Visualization of data


#### Used libraries 📚: ####
- Pandas
- Numpy
- Matplot lib