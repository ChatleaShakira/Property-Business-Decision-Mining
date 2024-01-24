# Data Mining and Business Intellegence
## Property-Business-Decision-Mining

In this case study, I aim to provide information relevant to the inquiries of the manager:

1. Data Quality of the Company
2. Recommendations for Data Improvement to DE/DBA
3. Trends in Housing Prices Among Cities
4. Recommendations for Next Branch Location:
5. Most Sold House Characteristics
6. Investment Recommendations within a Budget of Rp25 Billion
7. If RPPI intends to invest a maximum of Rp25 billion next week, leverage the data to recommend houses that have the potential to yield profits for the company.
8. Uncovering Additional Valuable Information from the Data
\
**Process:**

1. Preprocessing
a. Checking the data type
b. Handling noise and outliers
c. Handling missing values
d. Removing data duplication

**Insight**
1. The data held by PT Ray Pink Property Indonesia (RPPI) exhibits several shortcomings:
a. Missing Values:
All variables in the dataset contain missing values, with the highest counts as follows:
"hadap" variable: 1624 missing data
"garasi" variable: 1049 missing data
"carport" variable: 545 missing data
"listrik" variable: 225 missing data
b. Duplicate Data:
There are 14 instances of duplicate data.
c. Outliers:
Numerous outliers are present in the dataset.
d. Inconsistent Data Types:
The variables LT, LB, KT, and KM, which should have integer data types, are currently classified as object data types.
e. Inconsistency in Variable Values:
Inconsistencies are observed in the 'harga' variable, where values are sometimes prefixed with "RP," "Rp," or directly stated.
Despite these challenges, we believe that the existing variables are reasonably adequate for representing the characteristics of houses in each region. Addressing the data quality issues outlined above will be crucial for enhancing the reliability and usability of the dataset.
   
