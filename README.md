# Acute Abdominal Pain: Predictors of Hospital Admission

**Note:** To access the published version of the report on posit cloud connect please [click here](https://01a0031c-28e3-b342-8184-1ac73a363716.share.connect.posit.cloud) (use ctrl+click to open the link in another tab)

This project investigates which demographic, clinical, physical examination, and laboratory characteristics are associated with hospital admission among patients presenting with acute abdominal pain. Using a dataset of 957 patients, the analysis examined a broad range of patient characteristics, including comorbidities, pain location and characteristics, associated symptoms, physical examination findings, and laboratory measurements.

The analysis was conducted in R using R Markdown and included data preparation, missing-data assessment, exploratory data analysis, univariable statistical testing, and multivariable logistic regression. Chi-square tests, Fisher's exact tests, and logistic regression were used to identify variables associated with hospital admission. Variables demonstrating statistical significance in the univariable analysis were subsequently included in a multivariable logistic regression model to assess whether their associations remained after adjustment for other predictors.

Six variables remained statistically significantly associated with hospital admission in the multivariable model: vomiting, epigastric tenderness, lumbar tenderness, WBC, obstructive LFT findings, and lipase. RIF tenderness demonstrated borderline evidence of an association. The overall multivariable model demonstrated good discrimination between admitted and non-admitted patients, with an AUC of 0.879.

Several visualisations were developed to communicate the findings, including box plots, an adjusted odds-ratio forest plot, an ROC curve, and a heat map. The project also examined the findings in relation to previous clinical literature, considered potential explanations for the observed associations, and evaluated the strengths and limitations of the analysis.

The project demonstrates the application of statistical analysis, logistic regression, model evaluation, data visualisation, and evidence-based interpretation to a healthcare dataset.
