# Mapping Police Violence in the US 

The aim of this data science project is to delve into exploratory data analysis of the comprehensive dataset (publicly available at https://mappingpoliceviolence.org/) on the death of US citizens as a consequence of police brutality. The dataset is rich in information, with 60+ features to work with. Key features of the dataset include:

- Incident Date: The date when the incident occurred.
- Victim Name: The name of the person involved in the incident.
- Age: The age of the victim.
- Gender: The gender of the victim.
- Race: The race of the victim.
- Location: The geographical location of the incident.
- Cause of Death: The manner in which the death occurred.
- Details: Additional context or description of the incident.
- Source: The source of the information.

Link to the dataset: https://airtable.com/appzVzSeINK1S3EVR/shroOenW19l1m3w0H/tblxearKzw8W7ViN8

In this project, we investigate the following:

- Class imbalances or any marginalization/under-representation of ethnic minorities that are a part of the US Population (e.g., Hispanics, Blacks, etc.) with the help of OVR Logistic Regression and SMOTE.
- Using the temporal trends in police-related violence incidents to predict the number of deaths using Time Series Analysis (WMA)
- Suggest a solution to prevent such incidents in the future by using the data to incorporate situational training for police using a Random Forest Classifier. A better way to understand this solution is this: we can leverage the solution to predict the cause of death of a potential victim in a test situation based on the available data, and the police can then be trained to avoid that outcome in that particular situation.

For a comprehensive report on our findings, please refer to the provided Jupyter Notebooks or read our article here: https://medium.com/@abdulhaseeb494/3f8754e5045b.

Contributors: AbdulHaseeb Khan, Aazen Saleem, Ahmad Xoraiz Waheed, Ammar Hussain Uppal

For any queries regarding this project, feel free to email me at 25100325@lums.edu.pk
