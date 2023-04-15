# Seattle Airbnb Data Analysis
This repository contains an analysis of the Seattle Airbnb listings using the dataset from Kaggle.

## Dataset
The dataset in Kaggle consists of 3 files:
- `listings.csv`: including full descriptions and average review score
- `reviews.csv`: including unique id for each reviewer and detailed comments
- `calendar.csv`: including listing id and the price and availability for that day

The dataset can be downloaded via [Kaggle](https://www.kaggle.com/datasets/airbnb/seattle).
For the purpose of this analysis, we will only explore the `listings.csv` file.

## File Description
- .gitignore: Mentions all file extensions that are not pushed to Github, but used in local machine
- seattle-airbnb-data-analysis.ipynb: Notebook containing the data analysis
- README.md: Contains description about the repository

## Libraries Used
The following python libraries were used in this project.
- pandas==1.3.3
- numpy==1.21.2
- seaborn==0.11.2
- matplotlib==3.4.3

## Business Questions
There are several questions that we would like to answer using this analysis:
1. What are the most and least expensive neighborhoods to stay in Seattle?
2. How do listing prices vary by property type and room type?
3. Which amenities are associated with higher listing prices?

## Summary
In conclusion, through analyzing the data, we were able to identify the most common property types, room types, bed types, and amenities, as well as their relationship to listing prices. Additionally, we identified the most expensive neighborhoods to stay in and found that location is a significant factor in determining listing prices. Overall, the dataset offers a rich source of information for anyone interested in the Seattle Airbnb market, from potential hosts to curious travelers.
You can find the blog post regarding this analysis [here](https://medium.com/@adityautamawijaya/seattle-airbnb-better-experience-or-lower-price-4d7c18eca87b).

## Author
[Adi Wijaya](https://www.linkedin.com/in/aditya-utama-wijaya/)

## Acknowledgements
This dataset is part of Airbnb Inside, and the original source can be found [here](http://insideairbnb.com/get-the-data.html).
