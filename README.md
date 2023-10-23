# Car Price Prediction Project

## Overview

This repository contains a machine learning project that predicts car prices based on various features and attributes. The project leverages regression models and data preprocessing techniques to provide accurate price estimates for different vehicles.

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Data](#data)
- [Usage](#usage)
- [Machine Learning Models](#machine-learning-models)
- [Performance Evaluation](#performance-evaluation)
- [Contributing](#contributing)
- [License](#license)

## Project Structure

- `data/`: Contains the dataset used for training and testing the models.
- `notebooks/`: Jupyter notebooks for data exploration, preprocessing, and model building.
- `Images/`: Exported images of plots.
- `requirements.txt`: List of project dependencies.

## Getting Started

### Prerequisites

Before running the project, make sure you have the following prerequisites installed:

- Python (3.x recommended)
- Jupyter Notebook (optional, for running the notebooks)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/car-price-prediction.git

## Data
The project uses a dataset located in the data/ directory. The dataset contains information about various car attributes, including brand, model, year, mileage, and price. It is used for training and evaluating the machine learning models.

|S.No.| Serial number|
|Name| Name of the car which includes brand name and model name|
|Location| Location in which the car is being sold or is available for purchase (cities)|
|Year| Manufacturing year of the car|
|Kilometers_driven| The total kilometers (a unit used to measure length or distance) driven in the car by the previous owner(s)|
|Fuel_Type| The type of fuel used by the car (Petrol, Diesel, Electric, CNG, LPG)|
|Transmission| The type of transmission used by the car (Automatic/Manual)|
|Owner| Type of ownership|
|Mileage| The standard mileage offered by the car company in kmpl or km/kg|
|Engine| The displacement volume of the engine in CC|
|Power| The maximum power of the engine in bhp|
|Seats| The number of seats in the car|
|New_Price| The price of a new car of the same model in INR Lakhs (1 Lakh INR = 100,000 INR)|
|Price| The price of the used car in INR Lakhs|

## Usage
To run the project and make car price predictions, follow these steps:
1. Ensure you have completed the installation steps.
2. Explore the Jupyter notebooks in the notebooks/ directory for data analysis, preprocessing, and model building.
3. Use the Python scripts in the notebook to train and evaluate the models.

## Machine Learning Models
The project uses the linear regression model to predict car prices. You can find the model code and configurations in the jupyter notebook.

## Performance Evaluation
The project evaluates model performance using metrics like R-squared, RMSE, MAE, and MAPE.
![Model Comparison](images/model%20performance.PNG)

## Contributing
Contributions are welcome! To contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Make your enhancements or fixes.
4. Submit a pull request.