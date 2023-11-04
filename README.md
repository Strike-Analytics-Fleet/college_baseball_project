# Predicting College Baseball Pitchers' Performance Using Machine Learning  
  
This project aims to use machine learning techniques to predict the performance of college baseball pitchers based on historical data from 2015 to 2023 and provide valuable insights into the factors that contribute to a successful pitcher.  
  
## Table of Contents  
1. [Installation](#installation)  
2. [Usage](#usage)  
3. [Data](#data)  
4. [Methods](#methods)  
5. [Results](#results)  
6. [Conclusion](#conclusion)  
7. [Limitations and Challenges](#limitations-and-challenges)  
8. [Future Uses and Recommendations](#future-uses-and-recommendations)  
9. [License](#license)  
10. [Credits](#credits)  
  
## Installation  
  
No specific installation steps are required for this project. The necessary libraries can be installed using the following command:  
  pip install -r requirements.txt

  
## Usage  
  
To use this project, follow these steps:  
  
1. Clone the repository.  
2. Ensure you have the necessary libraries installed.  
3. Run the Jupyter Notebook or Python script that contains the analysis.  
  
## Data  
  
The datasets used in this project include historical data of college baseball pitchers from 2015 to 2023. The data contains individual statistics such as earned run average (ERA), strikeouts, saves, innings pitched, and other relevant metrics. The data has been sourced from the NCAA website (https://www.ncaa.com/stats/baseball/d1) and other relevant baseball statistics websites.  
  
## Methods  
  
The following methods were employed in this project:  
  
1. Data Collection: Collect and preprocess the historical pitcher data for Division 1 college baseball from 2015 to 2023.  
2. Data Cleaning and Preprocessing: Clean the data, handle missing or incomplete data, and convert categorical variables into numerical variables if needed.  
3. Feature Engineering: Create new features that may be relevant for predicting pitcher performance, such as the pitcher's win percentage, strikeout-to-walk ratio, or WHIP (Walks plus Hits per Inning Pitched).  
4. Machine Learning Model: Build various machine learning models, such as linear regression, decision trees, or random forests, and evaluate their performance using appropriate metrics such as mean squared error, R-squared, mean absolute error.  
5. Model Interpretation and Presentation: Analyze the importance of different features in the selected model and present the findings and implications for college baseball teams and coaches.  
  
## Results  
  
The Linear Regression model proved to be highly effective in predicting the pitching performance of college baseball teams, utilizing data from 2015 to 2023. The model's Mean Squared Error (MSE) is 0.0278, R-squared is 0.9538, and Mean Absolute Error (MAE) is 0.1279. The R-squared value of 0.9538 indicates that approximately 95.38% of the variation in the data can be explained by the model, which is a strong result.  
  
## Conclusion  
  
This model can aid college baseball teams, coaches, and talent scouts in making well-informed decisions regarding player recruitment and development. The team with the best predicted pitching performance for 2024 is Auburn, indicating their potential for success in the upcoming season.  
  
## Limitations and Challenges  
  
The limitations of this analysis include data availability, data consistency, model complexity, and ethical concerns. Challenges include incorporating additional data, exploring alternative machine learning models, and feature engineering efforts.  
  
## Future Uses and Recommendations  
  
The insights from this project can be applied in various ways, such as assisting college baseball teams and coaches in making data-driven decisions on player recruitment and development, helping talent scouts identify promising pitchers for professional drafts, providing a framework for analyzing the performance of pitchers in other baseball leagues like Major League Baseball (MLB), and
extending the analysis to other aspects of college baseball, including predicting team performance, batting performance, or overall player success. Based on the findings, it is recommended that college baseball teams and coaches utilize the insights from this analysis to inform their player recruitment and development strategies. Talent scouts can benefit from the model's predictions and feature importance analysis to identify promising pitchers for professional drafts. Additionally, further research exploring alternative machine learning models, feature engineering techniques, and additional data sources could enhance the model's predictive capabilities and provide more accurate predictions.  
  
## Implementation Plan  
  
1. Share the findings of this project with college baseball teams, coaches, and talent scouts.  
2. Collaborate with stakeholders to refine the model and incorporate additional data sources or features.  
3. Develop an interactive tool or dashboard that allows users to input their own data and receive personalized predictions and insights, such as SAS Viya or Power BI.  
4. Continuously monitor the model's performance and update it with new data as it becomes available.  
  
## Ethical Assessment  
  
Potential ethical considerations for this project encompass ensuring fairness and avoiding bias in the analysis and model predictions, respecting the privacy of players by avoiding the use of sensitive personal information, and transparently disclosing the limitations and uncertainties of predictions. To address these concerns, the project should maintain transparency in data collection, model development, and analysis, exclude sensitive personal information from the dataset, and carefully consider and address potential biases.  
  
## License  
  
[MIT License](LICENSE)  
  
## Credits  
  
- Project by Mark Fleet  
- DSC-680, Professor Catherine Williams  
- Bellevue University
- Data originally obtained through https://a.espncdn.com/sec/baseball/2023/lgteams.htm#leagt.mlb.  Data retrieved from 2015-2023, in separate csv files then combined for a single file for EDA and ML.  Also note due that this is a scaled back version referencing only the Southeast Conference in Division 1 and prediction is based on solely this conference. 

