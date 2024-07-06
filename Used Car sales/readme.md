## Determine the important features that drive the used car price
  
I tried different models to assess the importance of each attribute. e.g., LinearRegression, LinearRegression with polynomial degree 2, Ridge, Ridge with polynomial degree 2, Lasso and Lassow with polynomial degree 2. 
Based on the MSE value for each of these, the Ridge model with polynomial degree came out to be the best. To understand the importance of the features, I used permutation_importance on this model. Based on this the top 5 
attributes were: odometer, year, type, paint_color, and manufacturer

##### Based on this, we can derive that:  
**Odometer**: The lower the odometer reading, the higher the price  
**year**: The newer the car, the higher the price  
**type**: pickup and coup are popular type of cars that drives the price  
**paint_color**: The top 3 colors that drive the price are white, black, and yellow.  
**manufacturer**: Car price depends on the manufacturer. e.g., Ferrari, Aston-martin, tesla, Morgan have high resell value  
