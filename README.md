# HouseSalesPredictionAnalysis

<h2>Overview</h2>
<p>This dataset contains house sales prcies for over a year with the following features:</p>
<ul>
  <li>id :a notation for a house</li>
  <li>date: Date house was sold</li>
  <li>price: Price is prediction target</li>
  <li>bedrooms: Number of Bedrooms/House</li>
  <li>bathrooms: Number of bathrooms/bedrooms</li>
  <li>sqft_living: square footage of the home</li>
  <li>sqft_lot: square footage of the lot</li>
  <li>floors :Total floors (levels) in house</li>
  <li>waterfront :House which has a view to a waterfront</li>
  <li>view: Has been viewed</li>
  <li>condition :How good the condition is Overall</li>
  <li>grade: overall grade given to the housing unit, based on King County grading system</li>
  <li>sqft_above :square footage of house apart from basement</li>
  <li>sqft_basement: square footage of the basement</li>
  <li>yr_built :Built Year</li>
  <li>yr_renovated :Year when house was renovated</li>
  <li>zipcode:zip code</li>
  <li>lat: Latitude coordinate</li>
  <li>long: Longitude coordinate</li>
  <li>sqft_living15 :Living room area in 2015(implies-- some renovations) This might or might not have affected the lotsize area</li>
  <li>sqft_lot15 :lotSize area in 2015(implies-- some renovations)</li>
</ul>

<h2>Prelim Observation based on heat map</h2>
<p>
  After observing the data and graphs carefully, we can observe that the price is mostly dependent on the location, no of bedrooms, bathrooms, sqft living, sqft lot, floors, condition. We can note a few points:<br>

(1) The frequency of no of bedrooms=3,4 is higher than any other bedrooms. The price of these are mostly similar, but some have giher price than usual because of the other features like bathrooms, location, etc.<br>

(2) The heatmap identifies the correlations between the features which help us in identifying how the features are dependent on each other which cannot be known by seeing the data. (Example: sqft living is dependent on grade of the house)<br>

(3) The highest priced houses are sold in months: 9th to 11th. This shows people tend to spend more money on houses which are having more comforts in winter. <br>

(4) Most of the houses have sqft living in between 500 to 6000 irrespective of no of bedrooms. The higer the living space, the higher is the cost. <br>

(5) Price of the house is also dependent on sqft of lot (parking) as most people own their own car. <br>

(6) People are tending to pay less if the condition of the house is bad. They are spending more if the house is in good condition. <br>

(7) The 3d plot gives relationship between multiple features. <br>
</p>

<h2>Final Result</h2>
<p>
  Complex Model_3 gives us R-squared (testing) score of 0.759. From above reports, we can conclude that Polynomial regression is best solution.
</p>

I hope you liked this project :) <br>
-Cheers! 
