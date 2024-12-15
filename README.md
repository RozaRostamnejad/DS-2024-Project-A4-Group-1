# DS-2024-Project-Group-1

## Kaggle ClinVar: Predicting Whether a Genetic Variant Have Conflicting Clinical Classifications![image](https://github.com/user-attachments/assets/65bfb9a8-649a-488e-8470-180a4b497fbd)


This project is a part of the Introduction to Data Science course- LTAT.02.002 at University of Tartu.
Group A4: Ilze Polekauskaite, Liene Gutmane, Roza Rostam Nejad

# Dataset availability
Dataset available on Kaggle under the MIT License, Kevin Arvai, 2019. 
https://www.kaggle.com/datasets/kevinarvai/clinvar-conflicting/data 

Project A4: KAGGLE-CLINVAR
Predicting whether a genetic variant will have conflicting clinical classifications
We are using the ClinVar dataset for this analysis. Citation of the dataset : Kevin Arvai, 2019. Dataset available on Kaggle under the MIT License. https://www.kaggle.com/datasets/kevinarvai/clinvar-conflicting/data

The goal of this project is to predict if a gene variant will have a "conflicting" or "non-conflicting" classification using machine learning. It is problematic when variants have conflicting classifications, as this may hinder treatment, when the specific genetic cause, therefore, a target, cannot be established. The code we have written can help in seeing if the genetic variant is conflicting or not, and help the medical personnel to look out in case the genetic variant is conflicting, and perform more diagnoses.

# Contents (in order)
## 1. Data loading and Data Overview
In this section, we load the ClinVar Conflicting dataset and provide a quick summary of its structure.

## 2. Data Cleaning
In this section, we drop the unusable data. We drop all of the collumns with more than 70 percent of missing data.

## 3. Data Exploration
In this section, we explored the data set by visualizing different frequencies and proportion between different data: Number of Variants for each Class, Frequency of SIFT for each Class, Frequency of PolyPhen for each Class, Frequency of Symbols (1000+ Occurences), Proportion of Symbols for Classes, NUmber of Class 0 and 1 per Chromosome, Top 10 Most Represented Diseases by Class.

## 4. Machine Learning
In this section, we balanced the two classes, performed Logistic Regression, Random Forest, SVC, Gradient Boosting, Decision Tree, and KNN modelling, and evlauated them with AUC Scores.

## 5. Frequent Pattern Mining
In this section, we visualized the Support vs Confidence of Association Rules for Class and Symbol (of a gene), and the Classifications of the top 50 genes.

# Replication of Analysis
To replicate the same analysis, one can load the clinvar_conflicting.csv file, and copy the code in the same order as the code is.
