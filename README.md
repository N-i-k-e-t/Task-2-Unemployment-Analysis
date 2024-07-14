# Unemployment Rate Prediction in India

## Internship Details

* **Company:** The Black Pearls
* **Internship Period:** June 15, 2024 - July 15, 2024 

## Introduction

This project aims to analyze unemployment trends in India and build predictive models for unemployment rates using machine learning.  By leveraging historical unemployment data, the project explores patterns and relationships between various factors and unemployment levels.

**Business Context:**  While this project uses publicly available data, the insights and models developed have potential applications in several business contexts:

* **Workforce Planning:**  Understanding unemployment trends can inform hiring strategies, talent acquisition, and resource allocation within The Black Pearls.
* **Economic Analysis:** Insights into unemployment patterns can support the company's understanding of broader economic conditions, influencing investment and growth strategies.
* **Skill Gap Analysis:**  Analyzing unemployment data, particularly in specific regions or sectors, can reveal potential skill gaps, which can guide the company's training and development initiatives. 

## Dataset and Features

* **Data Source:**  Two datasets on unemployment in India were used for this project:
    * "[Unemployment_in_India.csv](link-to-dataset1)" (Provide the link if available)
    * "[Unemployment_Rate_upto_11_2020.csv](link-to-dataset2)" (Provide the link if available)
* **Features:**
    * **Date:**  Time period of the data.
    * **Estimated Unemployment Rate (%):**  Target variable for prediction.
    * **Region:** Geographic location within India.
    * **Estimated Employed:** Number of employed individuals.
    * **Estimated Labour Participation Rate (%):**  Percentage of the population actively participating in the labor force.
    * **Month:** Extracted from Date for seasonal analysis.
    * **Year:** Extracted from Date for yearly trend analysis.
* **Data Preprocessing:**
    * Missing values were handled by dropping rows (for simplicity in this analysis).
    * The 'Date' column was converted to a datetime object for time series analysis.
    * Month and Year features were extracted from the 'Date' column.

## Methodology

* **Approach:** Supervised machine learning was used for unemployment rate prediction. 
* **Algorithms:**  Three regression algorithms were explored:
    * **Linear Regression:** A baseline model to establish a linear relationship between features and unemployment.
    * **Decision Tree Regression:**  A tree-based model to capture non-linear relationships and interactions between features.
    * **Random Forest Regression:** An ensemble method combining multiple decision trees for improved accuracy and robustness.
* **Model Selection:**  Models were evaluated using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared on a test dataset.  The model with the lowest error and highest R-squared was selected as the best performing model.

## Results and Evaluation

* **Key Findings:** 
    * (Add your observations here, e.g., Did unemployment rates show seasonal patterns? Were certain regions impacted more? Was there a correlation between labor participation rate and unemployment?)
* **Performance Metrics:** 
    * **Linear Regression:**
        * MSE: 123.7006
        * RMSE: 11.1221
        * R-squared: 0.1456
    * **Decision Tree:**
        * MSE: 126.2545
        * RMSE: 11.2363
        * R-squared: 0.1279
    * **Random Forest:**
        * MSE: 85.3015
        * RMSE: 9.2359
        * R-squared: 0.4108
* **Visualizations:** (Optional) If you created relevant plots during data exploration or model evaluation, consider adding them to your project folder and linking them here. 

## Conclusion

* **Summary:**  This project successfully analyzed historical unemployment data from India.  The Random Forest model emerged as the most effective in predicting unemployment rates compared to Linear Regression and Decision Tree, achieving a lower RMSE and higher R-squared.
* **Business Implications:** 
    * The Black Pearls can leverage the insights from this analysis to support workforce planning decisions, such as understanding regional differences in unemployment for targeted recruitment.
    * The model can potentially be used as a tool to estimate future unemployment trends, informing strategic decisions related to hiring, resource allocation, and skill development programs. 
* **Future Work:**
    * Explore more advanced machine learning techniques, such as time series models (e.g., ARIMA, Prophet) or neural networks (e.g., LSTMs), which are often more suitable for time-dependent data like unemployment rates.
    * Incorporate additional relevant datasets, such as economic indicators (GDP, inflation), industry-specific data, or demographic trends, to improve model accuracy.

## Technical Information

* **Installation:**
    * Install the following Python libraries: 
        ```python
        pip install pandas matplotlib seaborn scikit-learn
        ``` 
* **How to Run:**
    1. Ensure you have the required libraries installed.
    2. Download the datasets and update the file paths in the code.
    3. Execute the provided Python script to perform data loading, preprocessing, model training, and evaluation. 

## Contact Information

* **LinkedIn:** [https://www.linkedin.com/in/niket-patil-/](https://www.linkedin.com/in/niket-patil-/ "https://www.linkedin.com/in/niket-patil-/")
* **Email:** niketpatil1624@gmail.com
