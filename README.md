# Predicting Type 2 Diabetes Using Multiple Logistic Regression in R

## Motivation for Project

The subject I’m investigating relates to diabetes mellitus, which affects approximately
37.3 million people in the United States, per the CDC. Diabetes is a chronic disease that
must be managed by various methods to control blood glucose levels. These methods
can vary depending if a person has Type 1 or Type 2 Diabetes. If blood glucose levels
are not properly managed, a variety of issues could arise such as kidney failure,
neuropathy, amputations, etc (Sanal et al. 2011). The motivation behind this subject is
that there is no known cure for diabetes, so identifying possible causes for this disease
could be the next step. In addition, I have a personal motivation for wanting to pursue
this subject as I have Type 1 Diabetes and know first hand how it can change
someone’s life. The question I’m attempting to answer is what explanatory variables can
be used to effectively predict whether someone will have Type 2 Diabetes? I’m
specifically interested in building a multiple logistic regression model that contains the
main explanatory variables that can make such a prediction. For a hypothesis, at least
one variable in the data set has a strong indication whether someone has diabetes.
The data set I wish to explore is about whether an individual was diagnosed with Type 2
Diabetes. 

## Notes

The project was completed in RMarkdown, so there are both code chunks and written work. 
For those who are interested in replicating or making improvements to my work, I have a 
separate file that only includes the R code. Additionally, the data set used has
also been included as a .csv file. 

Data was obtained from the National Institute of Diabetes and Digestive and
Kidney Diseases through the cooperation of women (ages 21 and above) of the Pima
Indian heritage. The data set includes 768 observations, 8 explanatory variables, and
one response variable. It should be noted that many of the covariates have missing
values, which were indexed using 0. These placeholders likely occurred because not
every subject was able to have all tests recorded. To correct this, I will be replacing the
missing values with the median of the covariates that have the issue (Joshi & Dhakal
2021). 

The response variable is called outcome, where it’s a binary response to whether a
subject has diabetes (0 = negative for diabetes and 1 = positive). The eight possible
explanatory variables contain two discrete variables (number of pregnancies and
Diabetes Pedigree Function) and 6 continuous variables (plasma glucose concentration,
blood pressure, skin fold thickness of triceps, serum insulin, BMI, and age).

## References 

Joshi, R. D., & Dhakal, C. K. (2021). Predicting Type 2 Diabetes Using Logistic
Regression and Machine Learning Approaches. International Journal of
Environmental Research and Public Health, 18(14).

Sanal, T. S, Nair, N. S, & Adhikari, P. (2011) Factors associated with poor control of
type 2 diabetes mellitus: A systematic review and Meta-analysis. Journal of
Diabetology 2(3):p 4.
