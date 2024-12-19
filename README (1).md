Here's the updated README with the deployed app link included:  

---

# Laptop Price Prediction  

This project predicts laptop prices based on their hardware specifications using machine learning. The workflow includes data analysis, model building, and deploying a predictive model as a web application using **Streamlit**.  

Check out the live web app here: [Laptop Price Prediction App](https://predict-laptop-price-swayam11.streamlit.app/)  

---

## Table of Contents  
1. [Project Overview](#project-overview)  
2. [Key Components](#key-components)  
3. [Tech Stack](#tech-stack)  
4. [Model Evaluation](#model-evaluation)  
5. [Web Application](#web-application)  
6. [Future Enhancements](#future-enhancements)  
7. [Contributing](#contributing)  

---

## Project Overview  

The dataset includes various features like RAM, storage, CPU, and GPU that influence laptop pricing. Using **Exploratory Data Analysis (EDA)**, we investigate these relationships and train machine learning models to predict laptop prices.  

The best-performing model is deployed as a user-friendly web app where users can input laptop specifications to receive an estimated price.  

---

## Key Components  

1. **Data Collection**:  
   The dataset includes features like:  
   - RAM (e.g., 8GB, 16GB)  
   - Storage (ROM, e.g., 512GB SSD)  
   - Processor (CPU, e.g., Intel Core i7)  
   - Display size and resolution  
   - Operating system, warranty, and brand  

2. **Exploratory Data Analysis (EDA)**:  
   Analyzing trends and relationships between features and price using visualizations to identify key predictors.  

3. **Model Building**:  
   - **Preprocessing**:  
     - Label encoding for categorical variables  
     - Standard scaling for numerical features  
     - One-hot encoding for categorical variables  

   - **Model Training**:  
     - Linear Regression  
     - Random Forest Regressor  
     - XGBoost (XGBRegressor)  
     - Support Vector Regressor (SVR)  

   - **Tools Used**:  
     - **Pandas**: Data manipulation  
     - **Scikit-learn**: Model building and evaluation  
     - **Joblib**: Model saving and loading  

   - **Best Model**:  
     - Linear Regression achieved an **R² score of 0.87**.  

4. **Web Application**:  
   Deployed using **Streamlit**. Users can input laptop specifications to get real-time price predictions.  

---

## Tech Stack  

- **Programming Language**: Python  
- **Libraries for Data Handling**:  
  - Pandas, Numpy  
- **Libraries for Visualization**:  
  - Matplotlib, Seaborn  
- **Machine Learning Frameworks**:  
  - Scikit-learn, XGBoost  
- **Deployment Framework**:  
  - Streamlit  

---

## Model Evaluation  

The models were evaluated based on the following metrics:  
- **R² Score**: To measure how well the model explains variance in price.  
- **RMSE (Root Mean Squared Error)**: To evaluate prediction accuracy.  

Linear Regression emerged as the best model with an **R² score of 0.87**.  

---

## Web Application  

The Streamlit app allows users to input the following specifications for price prediction:  

### Input Features  
1. **Brand**: Example: HP, Dell, Apple, etc.  
2. **Laptop Name**: Example: *Victus 15-fb0157AX Gaming Laptop*.  
3. **Processor**: Example: *5th Gen AMD Ryzen 5 5600H*, *Intel Core i7*.  
4. **CPU**: Example: *Hexa Core, 12 Threads*, *Quad Core*.  
5. **RAM**: Example: 8GB, 16GB, 32GB.  
6. **RAM Type**: Example: *DDR4*, *DDR5*.  
7. **Storage**: Example: *512GB*, *1TB*.  
8. **Storage Type**: Example: *SSD*, *HDD*.  
9. **GPU**: Example: *NVIDIA GeForce GTX 1650*, *AMD Radeon*.  
10. **Display Size**: Example: *15.6 inches*, *17.3 inches*.  
11. **Resolution Width**: Example: *1920* (for Full HD).  
12. **Resolution Height**: Example: *1080* (for Full HD).  
13. **Operating System**: Example: *Windows 10*, *Linux*, *macOS*.  
14. **Warranty**: Example: *1 year*, *2 years*.  

Users can fill these details to receive a price prediction instantly.  

Try the live web app here: [Laptop Price Prediction App](https://predict-laptop-price-swayam11.streamlit.app/)  

---

## Future Enhancements  

- **Additional Features**: Include details like battery life and display quality.  
- **Real-time Data Updates**: Integrate with live datasets for continuous updates.  
- **Advanced Models**: Experiment with deep learning models or ensemble methods.  

---

## Contributing  

We welcome contributions!  
1. Fork the repository.  
2. Create a new branch: `git checkout -b feature-branch-name`.  
3. Commit changes: `git commit -m 'Add some feature'`.  
4. Push to the branch: `git push origin feature-branch-name`.  
5. Submit a pull request.  

--- 

Let me know if there are further details or features you'd like to add!
