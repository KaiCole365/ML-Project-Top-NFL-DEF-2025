# NFL Top Defense 2025: Machine Learning Prediction

## Overview

This project uses machine learning techniques to predict the top 10 NFL defenses for the 2025 season. By analyzing historical team statistics, player performance metrics, 
and other relevant factors, the model aims to provide data-driven insights into defensive rankings for the upcoming 2025 NFL season. 
This analysis can be valuable for fantasy football enthusiasts, sports analysts, and NFL fans interested in understanding team strengths. Upon concluding the analysis,
my hope is that football fans will come away with just as much intrigue and suprises via the results as I did.

## Data Sources

*   **NFL.com:** Primary source for historical NFL team statistics, including defensive metrics.
*   **Pro-Football-Reference.com:** Used to add historical defensive statistics of 'Points Allowed'.

## Technologies Used

*   **Excel:** Used to populate worksheets with historical NFL defensive data.
*   **Python:** Primary programming language for data analysis, cleaning, and machine learning.
*   **Pandas:** Data manipulation and analysis.
*   **NumPy:** Numerical computing.
*   **Scikit-learn:** Machine learning algorithms and model evaluation.
*   **Matplotlib:** Data visualization.
*   **Seaborn:** Enhanced data visualization.

## Project Structure

The project is contained within the [Best Fantasy NFL Defense 2025.ipynb](https://github.com/KaiCole365/ML-Project-Top-NFL-DEF-2025/blob/main/Best%20Fantasy%20NFL%20Defense%202025.ipynb) Jupyter Notebook. 

The notebook is structured as follows:

1.  **Data Acquisition and Preprocessing:**
    *   Scraping or importing historical NFL data from various sources.
    *   Cleaning and formatting the data (handling missing values, outliers, etc.).
    *   Merging and transforming data into a suitable format for analysis.

2.  **Feature Engineering:**
    *   Creating relevant features from existing data, such as:
        *   Team defensive statistics (e.g., points allowed, sacks, interceptions, fumles recovered for TDs).
        *   Opponent-adjusted metrics.
    *   Selecting the most important features for the model.

3.  **Model Selection and Training:**
    *   Choosing appropriate machine learning algorithms for regression or classification (e.g., Random Forest, Gradient Boosting, Linear Regression).
    *   Splitting the data into training and testing sets.
    *   Training the model on historical data.
    *   Tuning hyperparameters to optimize model performance.

4.  **Model Evaluation:**
    *   Evaluating the model's performance using appropriate metrics (e.g., Mean Squared Error, R-squared).
    *   Validating the model on historical seasons to assess its accuracy.

5.  **Prediction and Ranking:**
    *   Using the trained model to predict defensive performance for the 2025 season.
    *   Ranking the top 10 NFL defenses based on predicted scores or probabilities by various metrics (e.g. INTs, Sacks, Recovered Fumbles for TDs)

6.  **Visualization and Analysis:**
    *   Creating visualizations to illustrate key factors driving defensive performance.
    *   Analyzing the characteristics of the top-ranked defenses.

7.  **Conclusions and Insights:**
    *   Summarizing the model's predictions for the 2025 season.
    *   Discussing the limitations of the model and potential areas for improvement.

## Key Findings

*   The model predicts the Broncos to be the top-ranked defense in the NFL for the 2025 season, with a total fantasy points score of 126.63. 
*   Key features driving defensive performance include:
    *   Sacks (53.15)
    *   Safties (1.52)
    *   Touchdowns from interceptions (2.26)
    *   Interceptions (14.58)
    *   Fumbles recovered for touchdowns (1.38)
*   The model's predictions are consistent with historical trends but may be affected by unforeseen events (e.g., injuries, coaching changes, free agency, retirements).

## How to Run the Code

1.  **Clone the repository:**
    ```
    git clone https://github.com/KaiCole365/ML-Sports-Analysis.git
    cd ML-Sports-Analysis
    ```

2.  **Install the required libraries:**
    ```
    pip install pandas numpy scikit-learn matplotlib seaborn 
    ```

3.  **Run the Jupyter Notebook:**
    ```
    jupyter notebook Top\ 10\ NFL\ DEF\ 2025.ipynb
    ```

## Potential Improvements

*   Incorporate more detailed player-level statistics and scouting reports.
*   Develop a more sophisticated model to account for injuries, coaching changes, and other dynamic factors.
*   Backtest the model on a longer historical dataset to assess its long-term accuracy.
*   Create an interactive feature for users to enter a team name and receive predicted 2025 stats/fantasy point results.

## Author

*   Kai Cole
