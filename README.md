# kaggle_home_default

This repo is for [Kaggle competition](https://www.kaggle.com/c/home-credit-default-risk) **Home Credit Default Risk**. 

## Data Source 
Click [here](https://drive.google.com/drive/folders/1fID6TWxyoAvP6Opfwo2dYpSexAW1T6yx) to download data. 

## Progress
**Week 1 (Jun 17)**: Create a repo to share data source, learnings and model code; Decide to conduct individual data exploration work for the following week.  

## Q&A
Share your questions and answers in [this Google doc](https://docs.google.com/document/d/1U8qMmTOcAPZmsL7fGNErXqK3kIJFMAx4tmgVCJB6SAw/edit). 

## Meeting Notes
6/23/2018 - Meeting 2

#### missing value: #### 
- multiple solution:
1. median
2. mean
3. ignore
4. naive bayes - regression 
    
- missing value flag
   
- Join table will generate more missing value 
1. aggregate new columns - differenciate people who has null 

2. using main table for model first
3. whether they applied before - add indicator

#### Categorical data: ####
- linear model: need to deal with
- Tree based model: can ignore

#### Colinearity: ####
1. correlation: if high -> remove?

2. sparse matrix/ similar columns:
- building
- documents
- address/building age

- Solution
1. check correlation
2. Random forest to check feature importance 
3. Feature generation: aggregate/feature selection (Linear Model); tree based model can ignore
4. numeric feature benefit for linear model; categorical feature good for tree based model


#### Next week: EDA for each table ####
- all     - train:  (307511, 122)
- all     - test:  (48744, 121)
- kris    - bureau_balance:  (27299925, 3)
- kris    - bureau:  (1716428, 17)
- Xi      - credit_card_balance:  (3840312, 23)
- Minqian - installments_payments:  (13605401, 8)
- Minqian - POS_CASH_balance:  (10001358, 8)
- Lu      - previous_application:  (1670214, 37)
