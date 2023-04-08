# Home_Sales_Analysis_SparkSQL
This project involves using SparkSQL to analyze home sales data and compute key metrics. The dataset includes information on home sales such as the number of bedrooms, bathrooms, floors, square footage, year built, and sale price.

The project requires creating temporary views, partitioning data, caching and uncaching a temporary table, and verifying that the table has been uncached. The project will involve using Spark to load and process the data, creating temporary views to represent the data, partitioning the data for faster processing, and caching and uncaching temporary tables to optimize query performance. 

## Average price for a four-bedroom house sold for each year
![1 Average price for a four-bedroom](https://user-images.githubusercontent.com/24644072/230701922-79326713-f2b7-4b9b-bf2a-6f1bd0e2bcbd.PNG)





## Average price of a home for each year it was built that has three bedrooms and three bathrooms
![2 Average price of a home for each year](https://user-images.githubusercontent.com/24644072/230701930-9a3c9e95-0229-42de-93ec-253eee98e5dd.PNG)




## Average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet
![3 Average price of a home for each year that has three bedrooms](https://user-images.githubusercontent.com/24644072/230701935-061d23f6-cef1-4938-b9b4-09148d14ed5c.PNG)





## "View" rating for homes costing more than or equal to $350,000
![4 View rating for homes](https://user-images.githubusercontent.com/24644072/230701938-3419259e-9ef1-4efa-8b95-927d320aa6ef.PNG)

![4-2 View rating for homes](https://user-images.githubusercontent.com/24644072/230701945-a89f474e-9a94-4aa2-858b-731221cfcf40.PNG)



## Comparing cached runtime with uncached runtime and parquet partioned runtime 

### uncached runtime
![5 Uncached](https://user-images.githubusercontent.com/24644072/230701956-0abfcb2d-bbb3-4bdf-8101-b02e16a0ac62.PNG)




### Cached runtime
![5 Cached](https://user-images.githubusercontent.com/24644072/230701961-034e639e-cf57-44d3-9e78-6943b5bf2334.PNG)



### After Parquet Partioned
![5 Parquet Partioned](https://user-images.githubusercontent.com/24644072/230701962-b9be587c-9835-43ed-9bea-ecbbf668e565.PNG)


## Summary

Overall, using cached data or the parquet DataFrame results in faster runtime as compared to querying the original data.
