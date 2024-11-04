# nhanes_inferential_2023
This assignment uses NHANES data to perform basic inferential statistics using Python in Google Colab, exploring relationships and differences in health metrics and demographic variables

## Questions to answer
Question 1: Is there an association between marital status (married or not married) and education level (bachelor’s degree or higher vs. less than a bachelor’s degree)?
Variables:
- DMDMARTZ (marital status) categorical
- DMDEDUC2 (education level) categorical
- The analysis test used is **chi-square**

Question 2: Is there a difference in the mean sedentary behavior time between those who are married and those who are not married?
Variables:
Variables: 
- DMDMARTZ (marital status, recoded) categorical
- PAD680 (sedentary behavior time, cleaned) continuous
- The analysis test used is **t-test**

Question 3: How do age and marital status affect systolic blood pressure?
Variables:
- RIDAGEYR (age) continuous 
- DMDMARTZ (marital status, recoded) categorical
- BPXOSY3 (systolic blood pressure) continuous
- The analysis test used is **ANOVA 2 way**

Question 4: Is there a correlation between self-reported weight and minutes of sedentary behavior?
Variables:
- WHD020 (self-reported weight, cleaned) continuous 
- PAD680 (sedentary behavior time, cleaned) continuous
- The analysis test used is **correlational**

Question 5: Is there a significant association between vitamin D deficiency and the prevalence of hepatitis B infection?
- Vitamin D Lab Interpretation (LBDVD2LC) categorical
- Hepatitis B Lab Antibodies (LBXHBS) categorical
- The analysis test used is **chi-square**
