# Air-Quality-Index-AQI-Prediction-Machine-Learning-Approach
This repository presents an AQI prediction project using machine learning, developed during an internship. It employs environmental data and modern algorithms to create a reliable model for air pollution management. Components include a dataset, random forest regression model, Jupyter notebook, Python scripts, and improvement recommendations.

# Overview  
This project predicts the **Air Quality Index (AQI)** based on key pollutants and environmental parameters using machine learning algorithms. The goal is to provide actionable insights into air quality, supporting data-driven decision-making for environmental management.  

The project includes data preprocessing, exploratory data analysis, and the implementation of a predictive model using **Random Forest Regression**. Results are visualized to understand patterns and evaluate model performance.  

---

# Project Structure  
---
# Features  
- **Data Cleaning**: Handles missing values, outliers, and normalization.  
- **Feature Engineering**: Identifies key pollutants impacting AQI.  
- **Model Development**: Implements **Random Forest Regression** for AQI prediction.  
- **Visualization**: Provides insights through heatmaps, boxplots, and AQI distribution.  
- **Deployment**: Future-ready for real-time predictions using **Streamlit**.  
---

# Setup  

# Prerequisites  
- Python 3.8+  
- Jupyter Notebook or an IDE of your choice.  
- seaborn==0.12.2  
- matplotlib==3.7.2  
- pandas==1.5.3  
- numpy==1.24.4  
- scikit-learn==1.2.2  

# Installation  
1. Clone the repository:  
   git clone https://github.com/your_username/AQI-Prediction.git

# Usage
Run the Notebook
Execute the AQI_Prediction.ipynb file in the notebooks/ folder to explore the analysis and model development.
Results
Training R²: 97.75%
Testing R²: 84.71%
Best Model: Random Forest Regression
These results indicate that the model effectively predicts AQI based on the provided dataset, demonstrating its potential for practical applications.

# Future Enhancements
Real-Time Integration: Integrate with IoT sensors for live AQI monitoring.
Better Algorithms: Explore advanced techniques like XGBoost or LSTM for improved accuracy.
Application Development: Build a user-friendly web app using Streamlit for visualizing predictions.
Incorporate Weather Data: Include meteorological factors like humidity and wind speed.

# License
This project is licensed under the MIT License.

# Contributing
Contributions are welcome! Feel free to fork this repository, create a branch, and submit a pull request.
