# Personality and Drug Consumption

Project Overview
- [Motivation](#motivation)
- [Research Questions](#rq)
- [Methodology](#methodology)
- [Conclusions](#conclusions)
- [Future directions](#futuredirections)
- [Presentation of the project](#presentation)

Getting started
- [Repository structure](#repo)
- [Dependencies](#dependencies)
- [How to run](#run)

## Motivation <a name="motivation"></a>
This project was motivated by the fact that drugs take a lot of lives. According to the CDC (2023) “In 2021, 106,699 drug overdose deaths occurred in the United States”. The main goal was to understand how different traits of personality interact with each other in determining the risk of drug consumption. Therefore, better prevention measures could be taken. 

## Research Questions <a name="rq"></a>
The two main research questions were:
1. Can we predict drug consumption based on personality?
2. Which dimensions of personality/combination of dimensions have more influence in determining drug consumption?

## Methodology <a name="methodology"></a>
To achieve the goal and answer the research questions, I utilized supervised machine learning algorithms for binary classification. I first conducted a detailed exploratory data analysis to get an understanding of the dataset's characteristics. I then employed various methodologies, including a decision tree classifier, a random forest classifier, logistic regression, and a deep learning model. To ensure optimal performance, I incorporated hyper-parameter fine-tuning techniques like grid search and cross-validation. Finally, I performed a thorough model evaluation by interpreting different metrics of the testing results, such as confusion matrix and recall scores. 

## Conclusions  <a name="conclusions"></a>
* Although none of the models proved to be sufficiently predictive, this experience allowed me to gain knowledge about the Machine Learning workflow and provided me with the necessary tools for future projects.
* Research Question 1 -  Personality by itself may not be enough to predict drug consumption.
* Research Question 2 - No dimension of personality or combination of dimensions were found to have an important influence.
* Other factors,  such as  demographics and life conditions should be taken into consideration.

## Future directions <a name="futuredirections"></a>
* Try collecting more data (with more variables, diverse demographics, and samples).
* Try using ensemble methods.

## Presentation of the project <a name="presentation"></a>
- [Slides for presentation of the project](https://www.canva.com/design/DAF-qJzHIY8/3lxNBafm2T4qWBzBc6a5kQ/view?utm_content=DAF-qJzHIY8&utm_campaign=designshare&utm_medium=link&utm_source=editor)
- [Video presenting the project](https://drive.google.com/file/d/1U0d5iA_lCYjTB0uFn75KX8PonKDrr6S6/view)

## Repository Structure <a name="repo"></a>

- Drug_Consumption.csv: personality and drug consumption data obtained from [Kaggle](https://www.kaggle.com/datasets/obeykhadija/drug-consumptions-uci)
- DrugsPersonality.ipynb: jupyter notebook containing exploratory data analysis, model exploration and evaluation
- README.md: this file

## Dependencies <a name="dependencies"></a>

- python 3.11.4
  
- numpy 1.23.5
- pandas 1.5.3
- graphviz 2.50.0
- matplotlib 3.7.1
- seaborn 0.12.2
- keras 2.12.0
- tensorflow 2.12.0

## How to run <a name="run"></a>

1. Clone the repository in a local machine
2. Use an integrated development environment such as VS code.
3. Make sure to have all the necessary dependendencies installed
4. Run
