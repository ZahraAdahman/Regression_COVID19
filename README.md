# Machine Learning Foundations:Exploratory Data Analysis course
## COVID19 Linear Regression Project

## Project title: 
'How does the trend of COVID19 cases relate to deaths?' - By Zahra Adahman,.
![image](https://user-images.githubusercontent.com/59964869/223543635-64a691ac-576b-40f2-984c-67148823e90c.png)

#### Sept. 30th, 2020.

## Background and Problem

Coronavirus disease (COVID19) was identified as a novel coronavirus following reports of an unknown respiratory infections sometime fatal, emerging from Wuhan, China. The COVID19 virus rapidly led to a pandemic, as it transmitted by air and contact, hence the swift spread across earth (2). Almost ever country has been inflicted by the virus.
The fatality of this disease is important to understand and track . As of moment, September 30th, 2020 over 33.7 million people has been confirmed infected and 1.01 million
dead from the disease. In united States of America alone, only 7 million has been infected and 206,000 people dead from the disease.

This project aims to understand the relationship between the number of total COVID19 case and the total number of deaths related to COVID19.

## Methodology 

* Python
* Jupyter Notebook
* Pandas Library
* Numpy Library 
* Seaborn Library
* ScikitLearn Library-Linear Regression


## Data

COVID19 data was obtained in July 2020 from Amazon Web Services (AWS) data exchange provided by IHME is an independent population health research
center at UW Medicine, part of the University of Washington. The .csv file provides more COVID19 data from countries around the world.
However, the fil e contains more detailed information of the United States of America (USA) and Canada by State/Province and country.

## Data Visualization 

![COVID_19_5](https://user-images.githubusercontent.com/59964869/97786655-6723d780-1b83-11eb-9b9a-c3b05625a592.png)

## Linear regression modelling
![image](https://user-images.githubusercontent.com/59964869/223544479-65830a24-e7d6-4426-9851-0bfcf7743d64.png)
![image](https://user-images.githubusercontent.com/59964869/223544540-6f992d42-436b-4cbf-a27c-65fdf412350a.png)
![image](https://user-images.githubusercontent.com/59964869/223544619-ea528a2b-3e62-4fb8-a152-9628ca8b21c7.png)
![image](https://user-images.githubusercontent.com/59964869/223544733-faf594ff-67bd-45a6-9d3e-55fb2866eeaf.png)

## Conclusion
* Considering the world COVID19 data to determine the linear relationship between the
number of COVID 19 death count and the number COVID 19 total case count isn’t
the best approach. This is because there are different elements that influence this
relationship in different countries and continents.

* In the USA, there are both unknown and known factors in the country that may have
caused the number of COVID 19 total case count increases as the number of COVID
19 death count increases between January and July, 2020. This model doesn’t
address it. 

* The linear model only shows a positive correlation between the number of COVID 19
death count and the number COVID 19 total case count.

* The next step will be applying this linear regression model to determine the
relationship between the variables in different countries. The R 2 score can serve as a
guage for risk of fatality in different levels such as state, province, or country level.
