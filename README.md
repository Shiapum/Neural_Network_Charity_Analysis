# Neural_Network_Charity_Analysis
## Overview
Create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
There are more than 34,000 organizations that have received funding from Alphabet Soup over the years.

Within this dataset are a number of columns that capture metadata about each organization, such as the following:

- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special consideration for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

## Results
### Data Preprocessing
What variable(s) are considered the target(s) for your model?
- IS_SUCCESSFUL (Target)


What variable(s) are considered to be the features for your model?
- APPLICATION_TYPE
- AFFILIATION
- CLASSIFICATION
- USE_CASE
- ORGANIZATION
- STATUS
- INCOME_AMT
- SPECIAL_CONSIDERATIONS
- ASK_AMT


What variable(s) are neither targets nor features, and should be removed from the input data?
- EIN and NAME

### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
![image](https://user-images.githubusercontent.com/21972342/157799410-c7702d1e-0690-4e75-8cfb-adbc7dc68d0a.png)

Were you able to achieve the target model performance?
No

What steps did you take to try and increase model performance?
- Tried to drop the Status colummn because maybe if you want to know if was successfu or not, doesn't depend in current status.
- Tried to increase the number of layers
- Tried to increase the number of epochs
