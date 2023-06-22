# Earthquake Data 
This repository contains code and resources for analyzing earthquake data. The goal of this project is to explore earthquake patterns and gain insights into seismic activity.

# Introduction
An earthquake is what happens when two blocks of the earth suddenly slip past one another. The surface where they slip is called the fault or fault plane. The location below the earth’s surface where the earthquake starts is called the hypocenter, and the location directly above it on the surface of the earth is called the epicenter.

On March 27, 1964, at 5:36 pm an earthquake of magnitude 9.2 occurred in Alaska. The depth of Alaska's (64) earthquake was  25 km beneath the surface. The earthquake lasted approximately 4.5 minutes. It was followed by multiple Tsunamis recorded as high as 67 meters. It still holds the title of the most powerful recorded earthquake in the history of the United States. It is also the second-largest earthquake ever recorded, next to the M9.5 earthquake in Chile in 1960. This catastrophic event was a  great leap forward to the modern age of earthquake science. Most of what we know about earthquakes can be traced back to the geological research done after the great Alaskan earthquake.

## Table of Contents

- [Business Overview](#business-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Conclusion](#conclusion)
- [Recommendations](#recommendations)
- [Next Steps](#nextsteps)
- [Contributing](#contributing)
- [License](#license)

## Business Overview

This project focuses on analyzing and predicting earthquakes using time series data. By leveraging historical earthquake data, the project aims to gain insights into earthquake patterns, develop accurate prediction models, and contribute to earthquake preparedness and risk assessment efforts. Through comprehensive data exploration and advanced time series forecasting techniques, the project seeks to uncover hidden patterns, understand the factors influencing earthquake occurrences, and enhance our ability to anticipate seismic events. The project's ultimate goal is to provide valuable information and tools that can assist in mitigating the impact of earthquakes and improving the overall resilience of communities prone to seismic activity.

## Installation

To use the code in this repository, you need to have the following dependencies installed:

- Python 3.7 or higher
- Jupyter Notebook or vscode or use google colab
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

## Data Understanding
The dataset sourc: [https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset](https://www.kaggle.com/datasets/usgs/earthquake-database)
The National Earthquake Information Center (NEIC) determines the location and size of all significant earthquakes that occur worldwide and disseminates this information immediately to national and international agencies, scientists, critical facilities, and the general public. The NEIC compiles and provides to scientists and to the public an extensive seismic database that serves as a foundation for scientific research through the operation of modern digital national and global seismograph networks and cooperative international agreements. The NEIC is the national data center and archive for earthquake information.

## Exploratory Data Analysis
This process was about the exploring of the data .Here we are looking at various univariate analysis and bivariate analysis . The section entail trend analysis,seasonal patterns and event clustering.

![alt text](https://github.com/Cynthiah-Mulwo/Phase_4_project/blob/master/map.png)

## Modeling

The modeling process involves building a machine learning time series model to find patterns and trends on the data and predict future earthquake occurences. ARIMA models have been used. 

## Evaluation

The evaluation of the models is based on several metrics, RMSE error, MSE error and mean. The performance of the models is compared, and the most suitable model is selected. 

## Conclusion

- Earthquake data analysis provides valuable insights for risk assessment. 
- Quality and availability of earthquake data are crucial for research. 
- Collaboration is essential for advancing earthquake research and preparedness.

## Recommendations

- Improve data collection and monitoring systems.
- Invest in advanced prediction models.
- Enhance collaboration and information sharing.
- Strengthen infrastructure resilience.
- Increase public awareness and education.

## Next Steps
- Refine and optimize prediction models for better accuracy.
- Conduct in-depth statistical analysis to identify trends and factors.
- Develop an integrated early warning system using real-time data.
- Educate and engage the public in earthquake awareness and preparedness

## Contributing

Contributions to this project are welcome. If you have suggestions, bug fixes, or enhancements, please submit a pull request or open an issue.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
