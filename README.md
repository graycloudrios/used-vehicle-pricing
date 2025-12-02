# What Drives Used Vehicle Prices


**Author**: Graycloud Rios is a seasoned technologist, storyteller, and creative thinker whose career spans decades in enterprise software engineering, financial systems, and AI innovation. Blending Native wisdom with modern tech, Graycloud crafts narratives, tools, and experiences that bridge tradition, transformation, and human connection.

File Structure:

  **./** - Directory containing Jupiter Notebook and README file
  
  Files:
  
  [VehiclePurchasePrice.ipynb](VehiclePurchasePrice.ipynb)

  README.md - This file
  
  **./data** - Directory containing the data file

  Files:
  
  [vehicles.csv](data/vehicles.csv)

  **./images** - Directory containing image files

  The notebook file associated with this exercise can be found here **==>>** [VehiclePurchasePrice.ipynb](VehiclePurchasePrice.ipynb)

## Data Description
The data used for this exercise consists of used-vehicle transactions in the United States. This exercise is to review the provided transactions to determine which vehicles will command a higher price and, therefore, assist used car dealers in selecting inventory with the best prices on the market.

The original dataset contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure speed of processing. Your goal is to understand what factors make a vehicle more or less expensive. Based on our analysis, we will provide clear recommendations to used-car dealerships on what consumers value in a used car.



## General Findings

* The data set contains a large number of missing attributes and what appear to be errors in the data (i.e., three cylinder trucks). This required a thorough scrubbing of the data set. The scrubbing resulted in a significantly reduced data set, which may detrimentally affect the analysis.
* The following models were used to analyse the data:
   *  Simple Linear Regression
   *  Linear Polynomial Feature Regression
   *  Polynomial Feature Ridge Regression
   *  Lasso Regression with Polynomial Features
   *  Linear Regression with Sequential Feature Selection
* Linear Polynomial Feature Regression proved to be the best model, having the best MSE and R2 values.
* By using the above model, the key attributes were identified. The most influential attributes are (in order of importance):
   * Age of the vehicle
   * Vehicle model
   * Number of Cylinders
   * Odometer Value
   * Fuel type
 * The remaining attributes were found not to have a significant effect on the vehicle's sale price.
 
## Dealer Recommendations
* When deciding on vehicle inventory to maximize sale price, the following characteristics should be taken into account:
  * Age: Vehicles less than six years of age
  * Vehicle Models: Trucks and utility vehicles, primarily Ford F-150 and Chevy Silverado models, are the best sellers.
  * Number of Cylinders: Within the most popular models, six or more cylinders are preferred by buyers.
  * Odometer Value: Higher Odometer values within the popular models remain best sellers. Higher Odometer values are not deterrents to sale.
  * Fuel Type: Gas engines remain in high demand over hybrids, diesel, and electric vehicles.
 * Reliability and utility, as shown in the most popular models, are the significant factors in the sale os a used vehicle.
 * Electric vehicles continue to improve and may provide greater reliability in the near future. Continued monitoring of market forces is necessary.

## Opportunities

* The significant opportunity is better data gathering techniques. The data suffers from missing values and incorrect entries. This will affect the predictions.
* Gathering data regarding the customers involved in the sale may provide a better prediction of vehicle preferences and understanding of the market.

