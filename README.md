# Employee-Departure-Survey-Analysis

## Introduction

This project is aimed at investigating the effect of employee dissatisfaction on the resignations in the Department of Education, Training and Employment (DETE) and the Technical and Further Education (TAFE) institute in Queensland, Australia.

This survey analysis project works with exit surveys from employees of DETE and TAFE.  

Management staff overseeing these depardments are interested in finding out overall, across both departments:
1. Are employees who only worked for the institutes for a short period of time resigning due to some kind of dissatisfaction? What about employees who have been there longer?
2. Are younger employees resigning due to some kind of dissatisfaction? What about older employees?


## Tools

- Programming Language: Python
- Libraries: Numpy, Pandas, Seaborn, Matplotlib


## Steps

1. Import data from both dete and tafe CSV files
2. Eliminate Unnecessary Columns
3. Clean column headers
4. Data cleaning and validation
5. Identify dissatisfied employees
6. Identify length of service
7. Combine both dataframes
8. Transform age column
9. Analyze consolidated data model and extract valuable insights

## Data Visualization and Insights

### Resignation due to dissatisfaction according to service length

![institute service](https://github.com/Jucodez/Employee-Departure-Survey-Analysis/assets/102746691/aab5dbe9-9155-44ca-a5bd-0762d1eb0e82)

#### Insights

1. New employees are not more likely to resign due to dissatisfaction.
2. Resignations among established and veteran employees are due more to dissatifaction than other employee segments.


### Resignation due to dissatisfaction according to age group

![age group](https://github.com/Jucodez/Employee-Departure-Survey-Analysis/assets/102746691/b662be66-e401-41b8-bb37-439c2fde8316)

#### Insights

1. About 42% of resignations among young employees can be attributed to dissatisfaction.
2. Middle-aged employees and seniors had the highest resignation due to dissatisfaction rates of 46% and 49% respectively.


### Project Extension: Resignation due to dissatisfaction according to institute

![Institute](https://github.com/Jucodez/Employee-Departure-Survey-Analysis/assets/102746691/85f50c59-7b26-4c1f-b046-2634032a5fa7)

#### Insights

1. Dete had a higher dissatisfaction rate of 49%
