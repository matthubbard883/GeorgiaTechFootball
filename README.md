# Georgia Tech Football: Coaching Eras Analysis

Analysis of Georgia Tech football performance across four coaching eras (2002-2024), using both logistic and linear regression to predict game outcomes.

## Research Questions
- How did offensive philosophy evolve across different coaches?
- Which statistics best predict wins under each coaching era?
- Can we predict both IF GT wins and BY HOW MUCH using regression models?

## Coaches Analyzed
- Chan Gailey (2002-2007)
- Paul Johnson (2008-2018)
- Geoff Collins (2019-2021)
- Brent Key (2022-2024)

## Methods
- Exploratory data analysis
- Correlation analysis
- Logistic regression (binary win/loss prediction)
- Linear regression (score margin prediction)
- 3 visualizations

## Key Findings
- Paul Johnson's triple-option offense was 62% rushing-based
- Turnover margin is the most consistent predictor of wins across all eras
- Logistic regression achieves ~75% accuracy in predicting wins
- Linear regression explains ~65% of score margin variance

## Requirements
- Python 3.8+
- pandas, numpy, matplotlib, seaborn, scikit-learn

## Usage
Open `gt_football_analysis.ipynb` and run all cells sequentially.
