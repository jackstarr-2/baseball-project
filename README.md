This project explores how team-level statistics in Major League Baseball relate to postseason success. It includes data collection (via Kaggle and web scraping), data cleaning and merging, machine learning models, and forecasts for the 2025 season.

The following datasets were used throughout this project to build, analyze, and forecast team performance:

team.csv: Team-level data from Kaggle containing offensive and batting statistics.

2025_playoff_prediction.csv: A forecasted dataset I created by predicting 2025 home run totals and identifying likely playoff teams based on those projections.

merged_1990_2024_data.csv: The final combined dataset that merges all sources for modeling and visualization.

The following Jupyter notebooks document the full analysis workflow for this project:

scraping_and_integrating.ipynb: This notebook handles web scraping, data cleaning, and merging of all relevant datasets into one master file.

project_questions.ipynb: This notebook answers the core analysis questions using machine learning models, visualizations, and a forecast of 2025 home run totals and playoff outcomes.