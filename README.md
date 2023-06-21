# Earthquake Data 
This repository contains code and resources for analyzing earthquake data. The goal of this project is to explore earthquake patterns and gain insights into seismic activity.

## Table of Contents

- [Business Overview](#business-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Business Overview

This project focuses on analyzing and predicting earthquakes using time series data. By leveraging historical earthquake data, the project aims to gain insights into earthquake patterns, develop accurate prediction models, and contribute to earthquake preparedness and risk assessment efforts. Through comprehensive data exploration and advanced time series forecasting techniques, the project seeks to uncover hidden patterns, understand the factors influencing earthquake occurrences, and enhance our ability to anticipate seismic events. The project's ultimate goal is to provide valuable information and tools that can assist in mitigating the impact of earthquakes and improving the overall resilience of communities prone to seismic activity.

## Installation

To use the code in this repository, you need to have the following dependencies installed:

- Python 3.7 or higher
- Jupyter Notebook
- Required Python libraries (numpy, pandas, scikit-learn, matplotlib, etc.)

You can install the required Python libraries by running the following command:
pip install -r requirements.txt


## Usage

To run the code and reproduce the analysis, follow these steps:

1. Clone this repository:

2. Navigate to the project directory:

3. Launch Jupyter Notebook:

4. Open the `Project.ipynb` notebook in your browser.

5. Follow the instructions in the notebook to execute the code cells and perform the analysis.

## Data
The dataset sourc: [https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset](https://www.kaggle.com/datasets/usgs/earthquake-database)
The National Earthquake Information Center (NEIC) determines the location and size of all significant earthquakes that occur worldwide and disseminates this information immediately to national and international agencies, scientists, critical facilities, and the general public. The NEIC compiles and provides to scientists and to the public an extensive seismic database that serves as a foundation for scientific research through the operation of modern digital national and global seismograph networks and cooperative international agreements. The NEIC is the national data center and archive for earthquake information.

## Modeling

The modeling process involves building a machine learning time series model to find patterns and trends on the data and predict future earthquake occurences. ARIMA models have been used. 

## Evaluation

The evaluation of the models is based on several metrics, RMSE error, MSE error and mean. The performance of the models is compared, and the most suitable model is selected. 

## Contributing

Contributions to this project are welcome. If you have suggestions, bug fixes, or enhancements, please submit a pull request or open an issue.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
