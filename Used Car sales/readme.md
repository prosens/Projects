Problem: Determine the important features that drives the used car price.
I tried different models to assess the importance of each attribute. e.g., LinearRegression, LinearRegression with polynomial degree 2, Ridge, Ridge with polynomial degree 2, Lasso and Lassow with polynomial degree 2. 
Based on the mse value for each of these, Ridge model with polynomial degree came out to be the best. To understand the importance of the features, I used permutation_importance on this model. Based on this the top 5 
attributes were: odometer, year, type, paint_color, and manufaturer

Based on this, we can derive that:
Odometer: Lower the odometer reading, higher the price
year: Newer the car, higher the price
type: pickup, coup are popular type of cars that drives the price
paint_color: White, black, yellow are top 3 colors that drives the price.
manufaturer: Car price depends on the manufacture. e.g., fearraru, aston-martin, tesla, morgan have high resell value
