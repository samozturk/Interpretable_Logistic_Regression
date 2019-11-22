# Interpretable_Logistic_Regression
##R Markdown reporting file of drug treatment report with Unesco Institute of Statistics data and Logistic Regression

  Intrepretable Machine Learning algorithms are very important if you are representing your model to non-technical people. You shoul be able to interpret your model and results to an audience without statistics and/or programming background.

  In this project I will walkthrough with codes and show you how to interpret your logistic regression model results. At the end of the project, logistic regression will be and intuitive algorithm rather than a mere black box. I am using R Markdown because it makes reporting process whole lot more easier.

  We will try to predict if a treated person will remain drug-free for 12 months or not. This is a real world data.
  
# DATA
UIS Drug Treatment study data
Description
There are 628 data points in the original data, 575 of which have no missing values.

Variable descriptions:

Variable_____Description___________________________Codes/Values

ID__________Identification Code________________________ 1 - 628

AGE_________Age at Enrollment	Years

BECK________Beck DepressionScore____________________0.000 - 54.000

IV__________History of IV Drug Use________________1 = Never_________2 = Previous_________3 = Recent

NDRUGTXT_____Number of Prior Drug Treatments______________0 - 40

RACE________Subject's Race_________0 = White_________1 = Non-White

TREAT_______Treatment Randomization Assignment______0 = Short____1 = Long

SITE________Treatment Site_______________________0 = A_________1 = B

DFREE_______Remained Drug Free for 12 Months________1 = Yes_________0 = No

Usage
data(uis)
Format
A data frame with dimension 575 by 18.

Source
Table 1.3 of Hosmer,D.W. and Lemeshow, S. (1998)

References
Hosmer,D.W. and Lemeshow, S. (1998) Applied Survival Analysis: Regression Modeling of Time to Event Data, John Wiley and Sons Inc., New York, NY
