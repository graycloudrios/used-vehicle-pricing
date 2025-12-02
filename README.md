# Used-Vehicle Pricing


**Author**: Graycloud Rios is a seasoned technologist, storyteller, and creative thinker whose career spans decades in enterprise software engineering, financial systems, and AI innovation. Blending Native wisdom with modern tech, Graycloud crafts narratives, tools, and experiences that bridge tradition, transformation, and human connection.

File Structure:

  **./** - Directory containing Jupiter Notebook and README file
  
  Files:
  
  [VehiclePurchasePrice.ipynb](VehiclePurchasePrice.ipynb)

  README.md - This file
  
  **./data** - Directory containing the data file

  Files:
  
  [vehicles.csv](data/vehicles.csv)

  The notebook file associated with this assignment can be found here **==>>** [VehiclePurchasePrice.ipynb](VehiclePurchasePrice.ipynb)

## Data Description
The data used for this exercise consists of used-vehicle transactions in the United States. This exercise is to review the provided transactions to determine which vehicles will command a higher price and, therefore, assist used car dealers in selecting inventory with the best prices on the market.

The original dataset contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure speed of processing. Your goal is to understand what factors make a vehicle more or less expensive. Based on our analysis, we will provide clear recommendations to used-car dealerships on what consumers value in a used car.



## General Findings

* The data set contains a large number of missing attributes and what appear to be errors in the data (i.e., three cylinder trucks). This required a thorough scrubbing of the data set. The scrubbing resulted in a significantly reduced data set, which may detrimentally affect the analysis.
* The following models were used to analyse the data:
     Simple Linear Regression
     Linear Polynomial Feature Regression
     Polynomial Feature Ridge Regression
     Lasso Regression with Polynomial Features
     Linear Regression with Sequential Feature Selection
  * test


## Opportunities

* Although the data gathered is intended for a population of drivers, it is vital to take into account pedestrian opportunities.
* Pedestrian traffic on the weekends is likely to provide greater coupon acceptance when people are looking for a place to go.
* Restricting to only drivers is limiting the audience artificially.
* There is no data in the observations regarding the day of the week. As can be seen from the data, those who are not in a hurry are more likely to accept the coupon. Identifying the day of the week will confirm the assumption that a lack of urgency creates an opportunity for coupon acceptance.

