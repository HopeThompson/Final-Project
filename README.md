1. Loading Necessary Libraries
You load libraries for:
•	Reading data from a CSV file.
•	Visualizing data with scatter plots and regression curves.
•	Tidying model outputs for better formatting and interpretation.
________________________________________
2. Reading and Previewing Data
You read the dataset into R and display the first few rows to ensure it has been loaded correctly. This step verifies that the data is ready for analysis.
________________________________________
3. Exploring the Data
You calculate summary statistics, which provide a high-level overview of the data’s distribution (e.g., mean, median, range). This helps identify potential issues like missing values or outliers.
________________________________________
4. Visualizing the Relationship
A scatter plot is created to examine the relationship between Time and Wakeful. It provides a clear visual representation of how one variable changes with the other.
________________________________________
5. Performing Linear Regression
You fit a simple linear regression model to quantify the relationship between Time (independent variable) and Wakeful (dependent variable). The model summary provides details like:
•	Coefficients: Strength and direction of the relationship.
•	R2R^2R2: Proportion of variance explained.
•	P-values: Statistical significance of the relationship.
________________________________________
6. Adding a Polynomial Regression Curve
You enhance the analysis by fitting a polynomial regression curve, which accounts for potential non-linear patterns in the data. This visualizes a more complex relationship, if present.
________________________________________
7. Checking Model Diagnostics
Diagnostic plots are used to validate regression assumptions:
•	Linearity: Ensure the relationship between variables is linear.
•	Normality: Residuals should follow a normal distribution.
•	Homoscedasticity: Residuals should have constant variance.
•	Influential points: Identify outliers or leverage points.
________________________________________
8. Making Predictions
You create predictions for new values of Time using the regression model. This includes confidence intervals, which show the range of likely outcomes.
________________________________________
9. Final Polynomial Regression Plot
A refined plot is generated, combining:
•	The original data points.
•	A polynomial regression curve to better represent the relationship.
________________________________________
10. Printing Model Metrics
You print:
•	R2R^2R2: Indicates how well the model explains the variation in Wakeful.
•	Regression equation: Expresses the relationship between Time and Wakeful in mathematical form, making it easier to interpret.
