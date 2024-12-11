# **Car Dheko - Used Car Price Prediction**

**Car Dheko** is a machine learning-based web application built using **Streamlit** to predict the price of used cars based on various features such as car brand, fuel type, body type, car model, and more. This project follows a comprehensive workflow from data cleaning and preprocessing to model development, evaluation, optimization, and deployment.

## **Project Overview**

This project aims to help users estimate the price of used cars using advanced machine learning techniques. The model is trained on historical car price data and utilizes various features like car brand, fuel type, body type, transmission, and others. The web application developed using **Streamlit** allows users to input car specifications and receive an estimated price for the car.

### **Key Features**
- **User-friendly web interface** built using Streamlit.
- **Car price prediction** based on various features.
- **Real-time predictions** for user-input car specifications.
- **Interactive visualizations** for data exploration and insights.

## **Project Workflow**

1. **Data Cleaning and Preprocessing**  
   The dataset is cleaned by removing missing values, handling categorical variables, and normalizing numerical data for model training.

2. **Exploratory Data Analysis (EDA)**  
   Performed to understand the relationship between features and car prices. Visualizations are used to identify trends and patterns in the data.

3. **Machine Learning Model Development**  
   Different regression models such as Linear Regression, Decision Trees, and Random Forests are trained and evaluated. The best-performing model is selected for predictions.

4. **Price Prediction Techniques**  
   A regression model is used to predict car prices based on the input features. The model is saved using **Joblib** for later use in the Streamlit app.

5. **Model Evaluation and Optimization**  
   Various metrics such as RMSE (Root Mean Squared Error) and R² score are used to evaluate model performance. Hyperparameter tuning is done to improve model accuracy.

6. **Model Deployment**  
   The model is deployed using Streamlit, providing a web interface for users to input their car details and get an estimated price.

7. **Streamlit Application Development**  
   A simple and interactive web application is built using **Streamlit** where users can enter car details and receive price predictions.

8. **Documentation and Reporting**  
   Complete documentation on how the project is structured and how the app can be used is provided.

## **Technologies Used**

- **Python** for data manipulation and machine learning model development.
- **Streamlit** for building the interactive web application.
- **Pandas**, **NumPy** for data cleaning and preprocessing.
- **Scikit-learn** for machine learning models.
- **Matplotlib** and **Seaborn** for data visualization.
- **Joblib** for model serialization.
- **Flask** (optional) if you decide to integrate with a full-fledged web application.

## **How to Run the Project**

1. **Clone the Repository**  
   Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your_username/Car-Dheko.git
   ```

2. **Install Dependencies**  
   Navigate to the project directory and install the required packages:
   ```bash
   cd Car-Dheko
   pip install -r requirements.txt
   ```

3. **Run the Streamlit App**  
   To launch the app, run the following command:
   ```bash
   streamlit run "Price prediction app.py"
   ```

   This will open the application in your default web browser.

## **Future Improvements**
- Add more features for car price prediction like mileage, year of manufacture, etc.
- Improve model accuracy by using more advanced algorithms or tuning hyperparameters further.
- Incorporate additional data for more robust predictions.

## **Contributing**

If you'd like to contribute to this project, feel free to fork the repository and submit pull requests. You can also raise issues for bugs, enhancements, or any feature requests.

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
