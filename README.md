# Lead-Scoring-Case-Study
Lead scoring model for X Education identifies potential leads using logistic regression to improve conversion rates and sales efforts.
## Overview
This repository contains the code and documentation for building a lead scoring model for X Education. The purpose of this model is to identify potential leads that are most likely to convert into paying customers. By assigning a lead score to each lead, the sales team can prioritize their efforts and focus on the most promising leads, increasing the lead conversion rate.

## Data
The dataset provided contains approximately 9000 data points with various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc. The target variable is the 'Converted' column, which indicates whether a past lead was converted or not (1 = converted, 0 = not converted). The data dictionary included in the zip folder provides more information about the dataset and the meaning of each attribute.

## Goals of the Case Study
The goals of this case study are as follows:

1. Build a logistic regression model: Develop a model that assigns a lead score between 0 and 100 to each lead. A higher lead score indicates a higher likelihood of conversion, while a lower score suggests a lower chance of conversion.
2. Handle additional problems: Address any additional problems presented by the company and adjust the model accordingly. These problems are outlined in a separate document provided.

# Requirements 
- Python 3
- Pandas 
- Matplotlib
- Numpy
- Logistic regression

## Getting Started
To get started with this project, follow these steps:

1. Clone the repository:<br>
```
git clone https://github.com/shakirahmad878/Lead-Scoring-Case-Study
cd x-education-lead-scoring
```

2. Install the required dependencies:<br>
```pip install -r requirements.txt```

3. Explore the data/ directory to familiarize yourself with the dataset and data dictionary.
4. Run the code in the src/ directory to preprocess the data, train the logistic regression model, and assign lead scores to the leads.
5. Review the documentation files in the docs/ directory, including additional_problems.md and presentation.ppt, for further insights and recommendations.

## Conclusion
Building an effective lead scoring model will enable X Education to prioritize potential leads, improve the lead conversion rate, and optimize the efforts of the sales team. By utilizing the logistic regression model and addressing the additional problems identified, X Education can enhance their lead generation process and increase their chances of converting leads into paying customers.

# Contact
If you have any questions or concerns, feel free to reach out to [shakirahmad878@gmail.com].
