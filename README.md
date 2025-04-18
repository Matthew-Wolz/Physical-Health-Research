# Wellness Factors Predicting Physical Activity as a Coping Mechanism

## Research Overview
This project investigates what aspects of wellness predict whether college students use physical activity as a coping mechanism for stress. The research was conducted under a Health Sciences professor at Truman State University and presented at the 38th Annual Student Research Conference.

**Research Question:**  
What other aspects of wellness predict whether one uses physical activity as a coping mechanism?

## Dataset
Analyzed survey data from first-year freshmen at Truman State University over five years. Key variable:

- **Physical_Activity_Stress**: Likert scale (1-4) response to: "I use physical activity as a coping mechanism to help deal with stress"

## Key Findings
1. **Strongest Predictors:**
   - Exercise (150+ mins/week): β = 0.31 (p < 0.001)
   - Strength training: β = 0.28 (p < 0.001)
   - Club sports: β = 0.14 (p = 0.007)

2. **Other Significant Factors:**
   - Learning new things (β = 0.15)
   - Sorority/fraternity involvement (β = 0.13)
   - Budget control (β = 0.08)

3. **Model Performance:**
   - Multiple Linear Regression R²: 0.502
   - Random Forest MAE: 0.629

## Methodology
### Analysis Techniques
1. **Exploratory Analysis**
   - Distribution visualization
   - Correlation analysis

2. **Predictive Modeling**
   - Multiple Linear Regression
   - Random Forest Regression

3. **Visualization**
   - Coefficient plots
   - Variable importance charts
   - Comparative boxplots

### Key Libraries
```python
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
import seaborn as sns
import statsmodels.api as sm
from sklearn.ensemble import RandomForestRegressor
from sklearn.metrics import (mean_absolute_error, mean_squared_error, r2_score)
```
## Implementation
The complete analysis code, including data processing, modeling, and visualization, is available in the Jupyter Notebook within the `Notebook` folder of this repository.

## Conclusion
This study provides empirical evidence that both physical activity behaviors and psychosocial factors significantly predict the use of physical activity as a stress-coping mechanism among college students. The findings offer actionable insights for student wellness programs and highlight potential intervention targets.
