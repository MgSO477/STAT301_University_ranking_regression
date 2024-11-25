# Linear Regression Analysis of University Rankings


## Project Overview
This study examines the relationship between **university overall scores**, **research scores**, and **geographic location** through a Multiple Linear Regression (MLR) model. By analyzing data from universities in the United States, Germany, and the United Kingdom, the project explores how research output and regional factors influence global university rankings.

## Dataset
The data includes:
- **Overall Score**: A composite metric of university performance.
- **Research Score**: A measure of research output and impact.
- **Location**: Regions (United States, Germany, United Kingdom).

Data was sourced from a credible global university ranking system.

## Methods
1. **Data Preprocessing**:
   - Handled missing values.
   - Encoded categorical variables for location.
2. **Exploratory Data Analysis (EDA)**:
   - Visualizations to explore relationships between variables.
   - Summary statistics.
3. **Assumption Checks**:
   - Residual plots to verify normality, homoscedasticity, and linearity.
4. **Regression Modeling**:
   - Built an MLR model with interaction terms.
   - Evaluated model performance using R-squared and RMSE metrics.

## Results
- **Key Findings**:
  - Research Score is a significant predictor of Overall Score, with a strong positive correlation.
  - Universities in the United States exhibit higher variability and overall scores than those in Germany and the UK.
  - No significant differences in overall scores were observed between German and UK universities after accounting for variability.
  - The model explains 90.81% of the variance (R-squared = 0.90806) with an RMSE of 3.7890.

- **Assumptions**:
  - Residual plots indicate that regression assumptions are largely met, supporting the model’s validity.

## Discussion
### Implications
- **For Universities**:
  - Prioritize research investment and international collaborations to boost rankings.
- **For Policymakers**:
  - Recognize regional disparities and provide equitable resources for research development.

### Improvements
- Address imbalanced data distributions by:
  - Including more universities from underrepresented regions.
  - Adding predictors such as faculty-to-student ratios or industry income scores.
- Use cross-validation to prevent overfitting and improve RMSE estimates.

### Future Directions
- Investigate additional predictors, e.g., teaching score, funding levels, and industry income.
- Explore regional policies' role in shaping university performance.
- Extend the study to universities in other regions for broader generalization.

## How to Access
1. Clone the repository:
   ```bash
   git clone https://github.com/MgSO477/STAT301_University_ranking_regression.git
   cd university-rankings-regression
    ```

2. Open the `301_Final report-4.ipynb` file for a detailed walkthrough of the analysis.
