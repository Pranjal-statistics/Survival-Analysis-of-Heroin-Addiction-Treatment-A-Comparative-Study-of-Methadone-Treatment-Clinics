![Heroin Additction Treatment](Heroin.jpg.webp)

# Survival-Analysis-of-Heroin-Addiction-Treatment-A-Comparative-Study-of-Methadone-Treatment-Clinics
This project examines the effectiveness of two different methadone clinics that treat heroin addicts. Methadone is a synthetic opiate proven useful for heroin addiction treatment; it blocks the effects of heroin and eliminates withdrawal symptoms.
The dataset used in this project contains information on 238 heroin addicts and compares the two clinics based on how long patients remain in treatment. The clinics differ according to their policies for patients (live-in vs. not).

The main variables in this dataset are:

## Patient ID
## Methadone treatment clinic (1 or 2)
## Drop out status (1 for drop out, 0 for censored)
## Time (in days) in treatment at the clinic until the patient dropped out (event) or was censored
## Prior prison record (1=yes, 0=no)
## Maximum pre-start methadone dose (mg/day)


## The analysis in this project involves:

> Kaplan Meier estimates for clinic and prison record
> Evaluation of proportional hazards assumption for clinic and prison
> Cox Proportional Hazards model for unadjusted effect of clinic on treatment dropout time
> Predicted probability of remaining in treatment for at least 60 days at each clinic
> Model comparison based on Akaike Information Criterion (AIC)
> Estimated coefficients and hazard ratios based on a chosen model
> Check for the assumption of proportional hazards for clinic, adjusting for prison and maxdose
> Testing for linear relationship between maxdose and log(HR)
> Fitting Exponential, Weibull, and Lognormal models to the outcome
> Calculation of hazard rate based on the exponential model
> Simulation of a randomized clinical trial to investigate the effect of adaptive servo-ventilation on the mortality and morbidity of patients with stable heart failure
> These analysis steps provide insights into the effectiveness of the two methadone clinics and the influence of various factors on treatment outcomes.

To replicate the project, download the dataset and the R script. Execute the scripts in your local environment to perform the analysis and generate the results.

This project requires a fundamental understanding of survival analysis and some experience with R or Python programming. Feel free to reach out with any questions or suggestions for improvement.
