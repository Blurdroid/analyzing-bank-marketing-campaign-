# analyzing-bank-marketing-campaign-
In this chapter, we will analyze data from the direct marketing campaign of a
Portuguese banking institution based on phone calls that were performed between
May 2008 and November 2010. We will not only use the techniques presented in
the previous chapters but will introduce new concepts, such as linear and logistic
regression, that are widely used in data analysis and predictive modeling (predictive
modeling being the process of using data patterns to predict future outcomes). These
types of models have several advantages, but two of the most important ones are
their simplicity and interpretability.

# plot the distribution of numerical and categorical columns and number of entries in y column 
in the numercical columsn the age and duration are seem a regular distrivution and the rest of columns are not since seem scattered and only few values are present 
we can derive that only 11% of the contacted customers
decided to accept the offer from the bank.

# run a hypothesis test in which we will test whether the average value of the respective numerical feature is different for "yes" entries for the y column against "no" entries for each numerical feature.
there is a statistically significant difference in
the mean values for each of the numerical columns

# kolomogorov smirnov
he distributions of the various numerical features present a significant difference between successful and
unsuccessful marketing campaigns.
# fifth: split two groups [campaign and finance]
most of the successful marketing campaigns were with newly contacted customers,
while a substantial peak is present for customers who were contacted the second
time, but without success

for lower values for the 3-month interest rates (the euribor3m
column), the number of successful marketing calls is larger than the number of
unsuccessful ones. The inverse situation happens when interest rates are higher. A
possible explanation for this phenomenon is customer optimism when interest rates
are lower.

# correlation between differnent numerical features with successfull and unseccusfull

we can observe from the preceding two figures, the correlation between
euribor3m and emp.var.rate is very high (approximately 0.93 for successful and
0.98 for unsuccessful calls). That is quite an interesting phenomenon as the first one
relates to the average interest rate at which European banks lend money to other
banks with a maturity of 3 months, while the second one relates to the employment
variation, that is, the rate at which people are hired or fired in an economy.

# what is the CPI ?
a measure of the average change overtime in the prices paid by urban consumers for a market basket of consumer goods and services.

# correlation differnce between numerical features with successfull and unsuccesffull

you can see the difference between the correlation matrices,
one for successful calls and one for unsuccessful calls. The values indicated in the
matrix can provide us with information about strong differences in correlations
between successful and unsuccessful calls. You can immediately see that there is a
significant difference in the correlations between the duration and emp.var.
rate columns for successful (correlation: 0.5) and unsuccessful (correlation:
0.0035) calls.
