# Data Analysis on Mobile Phone Features
## Overview
This is a data analysis done on the features offered by different mobile phones in a similar price range. **The objective of the analysis is to simplify the decision making process of customers by offering a curated list of mobile phones based on requirements**

#### Python Libraries used
- `numpy`
- `pandas`
- `plotly`

### Dataset
The dataset used contains the details of 1000 mobile phones in a similar price range along with their features. The dataset can be [found here](https://www.kaggle.com/iabhishekofficial/mobile-price-classification)

The dataset is cleaned by performing the following operations before using it for analysis:
- Checking for missing and inconsistent data
- Removing irrelevant columns
- Removing indices that do not satisfy certain conditions

## Exploratory Analysis
An exploratory analysis is done on the dataset to observe the relationship between different attributes and also to validate the assumptions made on them. This is done by visualising the attributes. A couple of examples are shown below

<img src="https://github.com/kk1708/mobile-phone-analysis/blob/main/images/battery%20and%20mobile%20weight.png" height="368" width="690">

The above scatter plot represents the relationship between battery power and mobile weight

<img src="https://github.com/kk1708/mobile-phone-analysis/blob/main/images/dual%20sim%20and%20talk%20time.png" height="368" width="690">

The above box plot represents the relationship between dual SIM and talk time

## Data Analysis
After cleaning up the data and observing the relationships between attribute, we analyse the dataset to present the best phones in each of the specified categories, which are:
- `The Daily Driver` -> For those who want reliable phones for daily use
- `The Cameraman` -> For those who use mobile phones as part of their photography or videography workflow
- `The Performer` -> For those who prioritise performance over everything else
- `The Monk` -> For those who want something simple, but robust without all the _smart features_

## Conclusion
The analysis is performed and the best phones in each of the specified categories are found
