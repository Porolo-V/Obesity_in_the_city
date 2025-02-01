###  Agreement between bioimpedance analysis and ultrasound scanningin body composition assessment
Observational single-centre cross-sectional study
___
**Authors:**
- Ivan Derkachev
- Nikita Zaitsev
- Valentina Saldaeva
- Alina Bozhko
- Viktoria Porolo


___
### Introduction

- Elevated body weight is associated with an increased risk of comorbid diseases;
- The burden on health care systems is rising;
- Only 5% of obesity cases are related to genetic factors and manifest in childhood;
- Metropolises have the most expressed fatogenic environment; the more urbanized the environment, the higher the prevalence of obesity.
-  BMI has previously been used to predict morbidity risks; but the outbreak of type 2 diabetes mellitus among people with normal BMI has shown the low sensitivity of BMI at the individual level.
- Revealing the phenomenon of hidden obesity: absence of obesity symptoms with reduced muscle and mineral mass (normal BMI with high fat percentage).
___
### Objective, tasks and data

**Primary objective:** Metrological analysis of the agreement of estimates of absolute values of fat and fat-free body mass, as well as the proportion of body fat obtained using bioimpedance analysis and ultrasound to determine the possibility of their interchangeability. 
**Additional objective:** Design of a formula for converting values from one method to another and evaluation of accuracy on a test sample.

**The following tasks were set in order to achive the goal:**

1. **Study of theoretical foundations and principles of metrological analysis of comparability of measurements**, including analysis by Pearson and Spearman correlation methods, Lin's coefficient and Bland-Altman analysis;
2. To **check the data for significant differences** in body composition estimates between the methods, taking into account the gender and morphological features of the subjects, and, if necessary, to  make stratification into subgroups;
3. **Examine correlations** between the results obtained by different methods for absolute values of fat and fat-free mass, as well as the proportion of body fat mass;
4. Assess the agreement of consistency of the measurement methods using **Lin's concordant correlation coefficient and Bland-Altman analysis**;
5. *If the consistency isn’t acceptable, analyse the shift in metrics estimates between methods using regression techniques such as: **linear regression, Deming regression and **Passing-Bablok** regression;** 
6. **Calculate a formula** for converting the results of one method to another and validate the accuracy on a test sample.
___
### Data overview
**Provided data:**

- ID;
- Age (full years);
- Sex;
- Height (cm);
- Weight;
- FM - Fat Mass (kg);
- BF - body fat proportion (%);
- FFM - Fat-free mass (kg);
- BIA - Bioimpedance analysis (Method 1);
- US - Ultrasound scanning (Method 2);

_*Body mass (Weight) = FM + FFM
*BF = FM/Body mass_

**Сalculated data:**

- BMI = Weight : (Height)²

_*Total number of observations (after removing 3 cases of misprints) - 276_

![Image](https://github.com/user-attachments/assets/98efe997-6b19-4a5d-9306-6cfe28de1954)

___
### Checking the data for significant differences:
Вody composition estimates between methods revealed the influence of sexual dimorphism on parameter estimates, so the data were **stratified by sex** into datasets data_male/data_female

![Image](https://github.com/user-attachments/assets/f06f7594-1ab4-4ff4-be36-f9617ae88804)
___

### Correlation and agreement analys results
- The **Pearson** correlation coefficients for the measurements of the two methods range from 0,83 - 0,97, indicating a very strong linear relationship between the BIA and ultrasound methods.

![cor_male](https://github.com/user-attachments/assets/2c54e274-28d9-4366-beb4-c5e90d226ebb)
![cor_fem](https://github.com/user-attachments/assets/cc43a7f7-b049-4345-8940-75dca2be053c)


- However, there is poor agreement by  **Lin’s concordance correlation coefficient** for most of the method comparisons.

![Image](https://github.com/user-attachments/assets/ad057a0d-7ab0-4cb5-819f-c528a3edeeef)

- **Bland-Altman analyses** also revealed significant differences and systematic shifts in parameter estimates between methods. 

![Image](https://github.com/user-attachments/assets/5619a93b-0d8b-45e4-ad81-649b7d2c31ee)

Based on these evaluations, we concluded that the **agreement between bioimpedance and ultrasound methods is not high enough to assume their metrological compatibility**, so we proceeded to the next objective, which was to calculate a formula for converting the measurements of one method to the other. 

___

### Regression

![Image](https://github.com/user-attachments/assets/b8c36137-79fc-4a7d-8efe-c4557dac5560)

### Adjusted Plots

![regression_new](https://github.com/user-attachments/assets/742d9bdc-7210-4579-9f70-e3173d26f4b8)
![corrected_reg](https://github.com/user-attachments/assets/1a2e0f0f-6a5f-4846-baa4-5e8f7659431f)

## Bland-Altman Plots after data correction 

![ba_new](https://github.com/user-attachments/assets/eba39985-e588-4740-8077-4be8d40da8c7)
---
# Conclusion

1. In the consistency analysis, Pearson correlation coefficients indicated a very strong linear relationship between the methods. However, the results of Lin's concordance correlation coefficient assessment showed weak agreement for most method comparisons. Combined with the Bland-Altman analysis, which revealed systematic biases and a tendency for one method to overestimate or underestimate values, this indicates an insufficient level of measurement agreement between the two methods.
2. After building the model and performing regression analysis, a formula was derived, data correction was applied, and the assessment of measurement interchangeability was repeated. As a result, the level of agreement between the metrics qualitatively improved.
3. After correcting systematic errors and improving measurement consistency, the data obtained using the two methods (or devices) became sufficiently consistent for direct comparison within our sample. However, to assess the accuracy of our formula, validation on other samples is required, for example, using machine learning methods.

