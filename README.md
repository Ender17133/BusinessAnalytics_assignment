# Assignment 4

## Question 1

The relationship between country credit ratings and the volatility of the countries’ stock markets was
examined in a study in the Journal of Portfolio Management (Spring 1996). The researchers point out
that this volatility can be explained by two factors: the countries’ credit ratings and whether the
countries in question have developed or emerging markets. Data on the volatility (measured as the
standard deviation of stock returns), credit rating (measured as a percentage), and market type
(developed or emerging) for a sample of 28 countries are in the attached data file.

a. Write a model that describes the relationship between volatility (y) and credit rating (x1) as two
nonparallel lines, one for each type of market. Specify the dummy variable coding scheme that
you use.

b. Plot volatility (y) against credit rating (x1) for all the developed markets in the sample. On the
same graph, plot y against x1 for all emerging markets in the sample. Does it appear that the
model specified in part a is appropriate? Explain.

c. Fit the model from part a to the data. Report the least squares prediction equation for each of
the two types of markets.

d. Plot the two prediction equations of part c on a scatterplot of the data.

e. Is there evidence to conclude that the slope of the linear relationship between volatility y and
credit rating x1 depends on market type? Test using alpha= 0.01.

f. Conduct a residual analysis for the model to check the assumptions on the error term.

## Question 2

Sales of single-family houses have been brisk in Mid City this year. This has been especially true in older,
more established neighborhoods, where housing is relatively inexpensive compared to the new homes
being built in the newer neighborhoods. Nevertheless, there are also many families who are willing to
pay a higher price for the prestige of living in one of the newer neighborhoods. The file MidCity120.xlsx
contains data on 120 recent sales in MidCity. For each sale, the file shows the neighborhood (1,2 or 3) in
which the house is located, the number of offers made on the house, the square footage, whether the
house if made primarily of brick, the number of bathrooms, the number of bedrooms, and the selling
price. Neighborhoods 1 and 2 are more traditional neighborhoods, whereas neighborhood 3 is a newer,
more prestigious neighborhood.
Use a regression model to estimate and interpret the pricing structure of houses in MidCity, and answer
the following questions based on the regression model.

a) Do buyers pay a premium for a brick house, all else being equal?

b) Is there a premium for a house in neighborhood 3, all else being equal?

c) Is there an extra premium for a brick house in Neighborhood 3, in addition to the usual premium
for a brick house?

d) For purposes of estimation and prediction, could neighborhoods 1 and 2 be collapsed into a
single “older” neighborhood?

## Question 3

Data on household food consumption was collected for a random sample of 26 households in Washington
DC. An economist wants to relate household food consumption, y, to household income, x1, and
household size, x2, with the first-order model:
E(y) = β0+β1x1+β2x2

a. Fit the model to the data. Do you detect any signs of multicollinearity in the data? Explain.

b. Is there visual evidence (from a residual plot) that a second order model may be more appropriate
for predicting household food consumption? Explain.

c. Comment on the assumption of constant error variance, using a residual plot. Does it appear to
be satisfied?

d. Are there any outliers in the data? If so, identify them.

e. Based on a graph of the residuals, does the assumption of normal errors appear to be reasonably
satisfied? Explain.

## Question 4

A medium sized automobile insurance company is interested in developing a regression model to help
predict the monthly collision claims of its policyholders. A company analyst has proposed modeling
monthly collision claims (y) in the Middle Atlantic states as a function of the percentage of claims by
drivers under age 30 (x1) and the average daily temperature during the month (x2). She believes that as
the percentage of claims by drivers under age 30 increases, claims will rise because younger drivers are
usually involved in more serious accidents than older drivers. She also believes that claims will rise as the
average daily temperature decreases because lower temperatures are associated with icy, hazardous
driving conditions. In order to develop a preliminary model, data were collected for the state of New
Jersey over a 4 year period. The data are in the attached file. Using only the last 3 years of data (months
13-48), answer the following questions.

a. Fit the complete second order model:
E(y) = β0+β1x1+β2x2+ β3x1x2+β4x1^2+ β5x2^2

b. Test the hypothesis H0: β4=β5=0 using alpha = 0.05. Interpret the results in practical terms.

c. Do the results support the analysts’ beliefs? Explain.
