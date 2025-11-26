# Do Coastal Regions in Turkey Have Better Well-Being?
## Sabancı University - DSA210 - Fall 2025 - Term Project

## Motivation
There is a popular debate about living happier in coastal towns. In my experience, people living in coastal towns argue that they couldn't ever live far from the sea. In response, people living far from the sea argue that it doesn't affect happiness or overall well-being. This topic have always seemed interesting to me. As a result I aim to shed light on the matter, working towards reasonable answers backed by official, legit data with this project.

## Introduction
With this project, my aim is to gather information about the average well-being of people living in different cities of Turkey and correlate this information with the cities they live in and specifically whether they have easy access to the sea. I plan to define "well-being" by several indicators such as unemployment rates, marriage and divorce rates, educational and cultural indicators, housing rates and more. Therefore I will be collecting data about these indicators of every province in Turkey, conduct exploratory data analysis, machine learning methods and eventually visualize the results.

## Research Questions
1. Do coastal provinces in Turkey have better well-being indicators compared to inland provinces?
2. Which indicators show the strongest differences between coastal and inland provinces?
#### Ultimately:
3. Does proximity to the sea correlate meaningfully with well-being when controlling the factors described above?

## Data Sources and Collection
All data will be collected from official TUIK Geographical Statistics Portal which offer not datasets, but helpful data on the well-being indicators from 2019 to 2024 via an interactive map. To perform analysis methods, I will be manually extracting the data from the interactive map and organizing the data in a spreadsheet format with every province of Turkey as the rows and statistical values and the coastal or inland status (1 for coastal and 0 for inland) as columns, thus creating one dataset that factors in several different variables for every province.

I decided the condition for a province being coastal or not, is if it's border touches the sea. I believe this will be a good projection of reality according to the research questions, since municipalities have their own public transport webs within the provinces, therefore people living in the non-coastal side also can reach the sea. Thus limiting the size of the project to province-level, not district-level.

The Portal: https://cip.tuik.gov.tr

## Methods

1. #### Exploratory Data Analysis
- I will be conducting EDA in order to compare coastal and inland provinces according to the controlled variables and identify the correlation between the indicators themselves. Exploring the dataset to have a better understanding of the factors that influence well being.



---

**Author:** Bora Burgazlıoğlu -34297

**Course:** DSA210  

**Semester:** Fall 2025

**Sabancı University**
