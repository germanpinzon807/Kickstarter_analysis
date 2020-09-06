# Kickstarter Crowdfunding Projects Analysis

Kickstarter is a crowdfunding platform where different creators show their projects. If people like the project, they can pledge money and fund it to make them a reality. This platform works over multiple countries around the world and almost any field of creative work can be found in it. Currently, is the biggest source of crowdfunding.

The general purpose of this project is to give a glimpse on how the diverse types of crowdfunding projects evolved in time and a notion of the most successful and failed types, all of this through the powerful lens of data analysis. In order to achieve this, I aspire to answer three questions, looking for insights that lie within a dataset that gather descriptions of almost 379000 projects ranging from 2009 (year in which Kickstarter was founded) to the first months of 2018, with features such as the type of project, the amount of money they collect or their country of origin. This dataset was gathered by Mickaël Mouillé with data provided by the Kickstarter platform itself (https://www.kaggle.com/kemical/kickstarter-projects).

All the analysis and results are contained in the notebook:

        Kickstarter Analysis Project Data Science Blog.ipynb

located within this repository.

The notebook have four parts:
- Description of the dataset and preparation of the data
- Question 1: What are the most successful, failed and canceled kind of projects?
- Question 2: Is there any seasonality on project launches?
- Question 3: What is the evolution of products launches through the years?

For any question, suggestion or discrepancy, feel free to write me at german.pinzon@davivienda.com


## Libraries needed:

You can run the notebook in a Python 3.7 environment with the following libraries installed:

- pandas (1.0.1)
- numpy (1.18.1)
- re (2020.7.14)
- seaborn (0.10.1)
- calendar 
- matplotlib (3.2.0)


## Repository Contents:

- Kickstarter Analysis Project Data Science Blog.ipynb: iPython notebook with analysis and results.
- ks-projects-201801.csv: Dataset.
- projects_evolution.png: Image result of anaysis.
- projects_launched.png: Image result of anaysis.
- projects_seasonality.png: Image result of anaysis.
- README.md


## Summary:

- Tech and Journalism projects are the most difficult type to get funded.
- A decreased in platform use by the project creators were identified since 2015.
- Dance and Theater projects are among the projects with less presence on the platform but are the most successful in funding too.


## Acknowlegdments:

I want to thank Mickaël Mouillé for the excellent dataset that allowed me to find insights of the Kickstarter platform and have fun on the way of discover them.