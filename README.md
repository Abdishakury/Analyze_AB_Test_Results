# Analyze A/B Test Results

## Introduction:

For this project, we will work to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. Our goal to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

A/B tests are very commonly performed by data analysts and data scientists. 

For this project, the results of an A/B test run by an e-commerce website.
- The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. 

My goal in this notebook is to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

## Software:

One can do this project in Jupyter Notebook. For doing this project one has to install the following packages -
- Pandas
- Numpy
- Matplotlib
- Statsmodels

## Project Steps:

### Data Wrangling:

- remove duplicates or records with missing or mismatched values
- handle the rows where the landing_page and group columns don't align

### Data Analytics:

- Compute probabilities of converting: 
    - regardless of page
    - Given that an individual received the treatment
    - Given that an individual received the control page
- Perform Hypothesis Testing and calculate p-values
- Conduct Logistic Regression


# NoteBook Content


Part I - Probability

Part II - A/B Test

Part III - A regression approach

## Conclusions

The findings show that the new and old pages have roughly equivalent chances of converting users, based on the statistical tests we conducted, the Z-test, logistic regression model, and actual difference identified. The null hypothesis is not rejected. I advise the e-commerce business to retain the old page. This would save you time and money by avoiding the need to establish a new website.
