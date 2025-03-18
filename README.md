# Houses-in-London-EDA
Houses in London Exploratory Data Analysis in Python

### Exploratory Data Analysis of Houses in London
This  notebook demonstrates data manipulation  using Python, with a focus on practical examples that are relevant for data analysis and interpretation. The key objectives of this notebook is Data Manipulation: Practical implementation of filter, map, and apply for working with pandas DataFrames. Techniques for extracting and transforming specific data points (e.g., extracting domain names from email addresses).

### Dataset Description
The dataset used contains hypothetical or real-world properties, including features like:
-	Emails: User emails (used for domain extraction examples).
-	Price (£): Property prices (used for correlation and visualization).
-	Building Age: Age of the building in years.
-	Square Meters: Property size in square meters.
-	Other categorical and numerical features.
### Purpose
This notebook is designed for: Demonstrating core Python programming concepts for data analysis (e.g., regex, lambda functions).
### Questions:
-	Calculate Price per Square Meter. Add a column price_per_sq_meter to calculate the price of the house per square meter. Use the formula: Price per Square Meter =  Price / Square Meters.
-	Flag Old and New Buildings. Create a column building_age_category: "New”  if Building Age <= 10.  "Old" if Building Age > 10.
-	Categorise by Garden Availability. Add a column garden_flag: True, if Garden is "Yes".  False otherwise.
-	Floor Count Category. Create a column floor_category:  "Single Floor"  if Floors = 1.  "Multi-Floor" if Floors > 1.
-	Luxury vs Affordable Neighborhoods. Create  a column neighborhood_category: "Luxury"  if the average Price (£) in the Neighborhood is greater than 2,000,000. "Affordable" otherwise.
-	Calculate Balcony Accessibility. Add a column balcony_accessibility_score: Score = 10 for "High-level Balcony".  Score = 5 for "Low-level Balcony".  Score = 0 for "No Balcony".
-	Material-Based Categorisation. Create a column material_category:  "Premium" for houses built with Marble, Granite, or Wood. "Standard" for other materials.
-	Analyse Garage Ownership. Add a column garage_flag: True if Garage is "Yes". False otherwise.

### Filter Practice Questions
-	List all properties with more than 3 bedrooms and located in Camden.
-	Filter out properties with "Old" building status and more than 50 years of age.
-	Find properties that have a garden and a garage but are not semi-detached.
-	Show properties where the price is above £2,000,000 and the view is "Park".
-	List all apartments with electric heating and high-level balconies.
-	Display properties in Westminster that are either "Renovated" or "Modern".
-	Filter out properties with "Street" view and "Industrial" interior style.

