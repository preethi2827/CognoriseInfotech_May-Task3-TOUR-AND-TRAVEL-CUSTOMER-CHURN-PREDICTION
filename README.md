# TOUR AND TRAVEL CUSTOMER CHURN PREDICTION

## Overview

This repository contains the implementation of a customer churn prediction model for a tour and travel company. The goal of this project is to predict whether a customer will churn (i.e., stop using the company's services) based on various indicators such as age, frequent flyer status, annual income class, services opted frequency, social media account synchronization, and hotel bookings. By predicting customer churn, the company can take proactive measures to retain customers and save resources.

## Dataset

The dataset used in this project includes the following features:
- `Age`: The age of the customer.
- `FrequentFlyer`: Whether the customer is a frequent flyer or not.
- `AnnualIncomeClass`: The annual income class of the customer.
- `ServicesOptedFrequency`: How frequently the customer opts for services.
- `SocialMediaSync`: Whether the customer's social media account is synchronized with the company.
- `HotelBookings`: The number of hotel bookings made by the customer.
- `Churn`: The target variable indicating whether the customer churned (1) or not (0).

The dataset is freely available and was used for practice and in a hackathon setting.

## Project Structure

The project is organized into the following directories and files:

```
Tour-and-Travel-Customer-Churn-Prediction/
│
├── data/
│   └── customer_churn_data.csv          # Dataset file
│
├── notebooks/
│   └── Customer_Churn_Prediction.ipynb  # Jupyter Notebook with data analysis and model
│
├── models/
│   └── churn_prediction_model.pkl       # Saved predictive model
│
├── visuals/
│   └── *.png                            # Visualization images
│
├── README.md                            # Project documentation
│
└── requirements.txt                     # Python dependencies
```

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Tour-and-Travel-Customer-Churn-Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Tour-and-Travel-Customer-Churn-Prediction
   ```
3. Create a virtual environment and activate it:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/Customer_Churn_Prediction.ipynb
   ```
2. Follow the notebook to perform data analysis, visualization, and build the predictive model.

## Analysis and Modeling

The notebook includes the following sections:

1. **Data Loading and Preprocessing**: Importing the dataset and handling missing values, if any.
2. **Exploratory Data Analysis (EDA)**: Visualizing the data to understand the distribution and relationships between features.
3. **Feature Engineering**: Creating new features and preparing the data for modeling.
4. **Model Building**: Training different machine learning models to predict customer churn.
5. **Model Evaluation**: Evaluating the performance of the models using appropriate metrics.
6. **Visualization**: Visualizing the results to gain insights.

## Results

1.EXTRACT INSIGHTS 
2.EDA
3.DATA FORMATTING
4.VISULIZATION OF DATA 

## Contributing

Contributions are welcome! If you have any improvements or suggestions, please create a pull request or open an issue.

## Contact

For any questions or feedback regarding this project, feel free to reach out to me via:

LinkedIn: linkedin.com/in/preethid28 GitHub: github.com/preethi2827

## Acknowledgements

Special thanks to the contributors and the community for their support and the open datasets available for practice.


