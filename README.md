#HYPOTHESIS TESTING

#BUSINESS UNDERSTANDING

Autolib' was an electric car sharing service which was inaugurated in Paris, France, in December 2011.It was operated by the Bolloré industry and complemented the city's bike sharing system, Velib', which was set up in 2007. The Autolib' service maintained a fleet of all-electric cars for public use on a paid subscription basis.

#Problem Statement

Autolib service board claims that all the Utilib 1.4 cars picked during the weekend are returned and this makes it easier for them to do their maintenance faster than the other two Autolib electric car models . I will do a hypothesis test to test if this claim is factual.

#Hypothesis

Null Hypothesis - The number of Utilib 1.4 taken over the weekend is equal to the number of Utilib 1.4 electric cars returned on the weekend.

Alternative hypothesis - The number of Utilib 1.4 taken over the weekend is not equal to the number of Utilib 1.4 electric cars returned on the weekend.

#DATA DESCRIPTION

We are using a dataset provided by the Autolib electric cars company. Below is the dataset description:

 Autolib dataset http://bit.ly/DSCoreAutolibDataset , this dataset contains data collected for a period of six  months from January to June in the year 2018.

#HYPOTHESIS TESTING PROCEDURE

#Step 1.
Stating the hypothesis
Null Hypothesis - The number of Utilib 1.4 taken over the weekend is equal to the number of Utilib 1.4 electric cars returned on the weekend.
Alternative hypothesis - The number of Utilib 1.4 taken over the weekend is not equal to the number of Utilib 1.4 electric cars returned on the weekend.

#Step 2.
Defining the population
from the dataset l selected the columns that l will be working with for my hypothesis testing.
I selected the Utilib 1.4 taken and Utilib 1.4 returned during the weekends

#Step 3.
Sample size
From my sample population l used simple random sampling to select my sample size . My sample size was 20.
sample_Utilib 1.4 Return sum = [ 2, 15,  2,  1,  3,  2,  0,  1,  7, 37,  0,  0,  2, 10,  1,  1, 20,13, 22,  0]
Sample_utilib 1.4 Taken sum = [1, 13,  3,  2,  4,  1,  0,  1,  5, 35,  0,  0,  1, 10,  0,  3, 19, 10, 22,  0]

#Step 4.
Computing the test value and p-value and alpha level
My alpha level = 0.05
I used two sample t-test because;
 I had two independent sample groups with unknown mean of the population.
The data was continuous
Data in each group must be obtained via a random sample from the population.
Data in each group are normally distributed -  Rules of thumb say that the sample means are basically normally distributed as long as the sample size is at least 20 or 30. For a t-test to be valid on a sample of smaller size, the population distribution would have to be approximately normal.

#HYPOTHESIS TESTING RESULT

p-value of the test =  0.8832389582790855
T.test Statistic =  -0.14785501676175575

Mean of sample 1 = 6.5
Mean of sample 2 = 6.95
Full hypothesis testing can be found in this colaboratory notebookolab.research.google.com/drive/1iLE_JKD0E4-HfQcRZhaRS2u8M9nnawDP#scrollTo=fEpsah5dvg-u .

#Hypothesis test decision

(p-value)0.88 > significance level(0.05)
our p-value is greater than the significance level so will fail to reject the null hypothesis that, The number of Utilib 1.4 taken over the weekend is equal to the number of Utilib 1.4 electric cars returned on the weekend..

#DISCUSSION OF TEST SENSITIVITY

Statistics power test  is only relevant when the null hypothesis is false. The statistical power of a hypothesis test is the probability of correctly rejecting a null hypothesis or the likeliness of accepting the alternative hypothesis if it is true. So, the higher the statistical power for a given test, the lower the probability of making a Type II (false negative) error.

I did not test for sensitivity because l failed to reject my null hypothesis.

#SUMMARY AND CONCLUSION

There is  enough evidence to support the claim that the number of Utilib 1.4 taken over the weekend is equal to the number of Utilib 1.4 electric cars returned on the weekend.

our p-value is greater than the significance level so will fail to reject the null hypothesis that, The number of Utilib 1.4 taken over the weekend is equal to the number of Utilib 1.4 electric cars returned on the weekend.

#RECOMMENDATION

To make it easy for the service and maintenance of all the electric cars under the Autolib company, all cars taken either during the weekend or weekend should be returned to the station. Late return of the cars to the station makes it hard for the maintenance and servicing of the cars.
