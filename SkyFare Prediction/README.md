# SkyFare-Prediction

This project aims to predict airline fares using data analysis and machine learning techniques. The dataset used contains information about flights, including factors like airline, source, destination, departure time, duration, and more.

## Project Structure

### 1. Data Preprocessing
- **Handling Null Values**: Checked and dropped null values to ensure data consistency.
- **Data Cleaning**: Various preprocessing steps were performed, such as dealing with outliers and removing unnecessary features.
- **Feature Engineering**: New features were created based on the existing data to improve model performance.

### 2. Exploratory Data Analysis (EDA)
- **Flight Timing Analysis**: Investigated when most flights take off.
- **Impact of Duration on Price**: Analyzed how flight duration impacts the fare.
- **Airline vs. Price**: Compared different airlines to understand their pricing patterns.
- **Route Analysis**: Identified the most used routes, particularly for the Indigo airline.

### 3. Feature Encoding
- **One-Hot Encoding**: Applied to categorical features to prepare them for machine learning models.
- **Target Guided Encoding**: Used for encoding ordinal data.
- **Label Encoding**: Employed for features with a natural order.

### 4. Model Building
- **RandomForest Regressor**: A robust machine learning model used for predicting airline fares.
- **Automating ML Pipelines**: Implemented steps to automate the machine learning workflow.
- **Hyperparameter Tuning**: Fine-tuned the model parameters for optimal performance.

## How to Run the Project

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/Airlines-Fare-Prediction.git
    cd SkyFare-Prediction
    ```

2. **Install the required packages**:
    Ensure you have Python installed, then run:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebook**:
    Open the notebook in Jupyter and execute the cells to see the analysis and results.

## Results and Conclusion
The final model was able to predict airline fares with a high degree of accuracy, highlighting key factors that influence pricing. This project demonstrates the effective use of data preprocessing, feature engineering, and machine learning for predictive analysis in the airline industry.

## Tools and Libraries Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

## Future Work
Further improvements could include trying different models, such as Gradient Boosting or XGBoost, and incorporating more features such as weather data or economic indicators that might influence airline pricing.
