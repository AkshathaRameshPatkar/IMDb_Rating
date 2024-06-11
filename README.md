# Movie Metadata Analysis and Predictive Modeling
This project involves the analysis and predictive modeling of movie metadata to derive insights and build predictive models for IMDb scores and movie success. The dataset used is the "movie_metadata.csv" file, which includes various attributes of movies such as budget, gross earnings, IMDb scores, and genres.

## Project Overview
1. **Data Cleaning and Preprocessing**:
    - Imputed missing values for 'gross' and 'budget' with median values.
    - Dropped rows with remaining missing values.
    - Created a 'main_genre' column to categorize movies by their primary genre.
    - Removed outliers using z-score thresholding.
2. **Exploratory Data Analysis (EDA)**:
    - Visualized the distribution of IMDb scores across different genres using box plots.
    - Analyzed the number of movies released per year and per genre with bar plots.
    - Created a treemap to visualize the distribution of movie genres.
    - Generated a heatmap to show correlations between numerical features.
3. **Feature Engineering**:
    - Added a new column 'num_genres' to indicate the number of genres associated with each movie.
4. **Predictive Modeling**:
    - **Regression Models**:
        - Built and evaluated multiple regression models to predict IMDb scores, including Linear Regression, Decision Tree Regressor, Support Vector Regressor, and K-Neighbors Regressor.
        - Linear Regression performed best with an MSE of 0.67 and MAE of 0.65.
    - **Classification Models**:
        - Created a 'movie_status' column to classify movies as 'hit' or 'flop/average' based on budget and gross earnings.
        - Evaluated several classification models, including Support Vector Classifier, K-Neighbors Classifier, Decision Tree Classifier, Random Forest Classifier, and Logistic Regression.
        - Random Forest Classifier achieved the highest accuracy of 83%.


## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Squarify
- Scikit-learn

## How to Run
1. Clone the repository.
2. Install the required libraries.
3. Run the Jupyter notebook or Python scripts to explore the analysis and models.

## Conclusion
This project provides a comprehensive analysis of movie metadata, including effective data preprocessing, insightful visualizations, and robust predictive modeling. The models developed can help in predicting movie success and understanding key factors that influence IMDb scores.

Feel free to contribute or provide suggestions to improve this project!
