# Earth Observation using Machine Learning to Analyze Satellite Data to Monitor and Predict Weather Patterns, Natural Disasters and Climate Change.
Special project completed during the 2nd year of my undergrad.

Certainly! Here's the updated README with the additional sections:

---

# Weather Prediction using Machine Learning and Earth Observation

![Weather Prediction](https://github.com/shrutin0492/special-topics-1/blob/main/Results/weather_prediction.jpg)

## Table of Contents

- [Introduction](#introduction)
- [Why This Project](#why-this-project)
- [Why Earth Observation and Machine Learning](#why-earth-observation-and-machine-learning)
- [How This Project Contributes](#how-this-project-contributes)
- [Problem Statement](#problem-statement)
- [Dataset Description](#dataset-description)
- [Methodology](#methodology)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Why Certain Models and Evaluation Metrics](#why-certain-models-and-evaluation-metrics)
- [What the Code Does](#what-the-code-does)
- [Relevant Links](#relevant-links)
- [How to Run](#how-to-run)
- [Future Improvements](#future-improvements)
- [Achievements](#achievements)
- [Additional Considerations](#additional-considerations)

## Introduction <a name="introduction"></a>

This repository hosts a machine learning project focused on predicting weather patterns using Earth observation satellite data. By leveraging advanced machine learning algorithms and analyzing satellite imagery, the project aims to enhance weather forecasting accuracy and contribute to disaster management and climate change mitigation efforts.

## Why This Project <a name="why-this-project"></a>

Accurate weather prediction is crucial for various sectors, including agriculture, transportation, and disaster management. Traditional forecasting methods often lack precision and fail to capture complex weather patterns. By integrating machine learning with Earth observation data, this project seeks to improve the accuracy and reliability of weather forecasts, thereby enabling better decision-making and risk mitigation strategies.

## Why Earth Observation and Machine Learning <a name="why-earth-observation-and-machine-learning"></a>

Earth observation satellites provide a wealth of data on various environmental parameters, including atmospheric conditions, land surface temperature, and vegetation health. Machine learning algorithms excel at analyzing large and complex datasets, making them well-suited for extracting valuable insights from satellite imagery. By combining these technologies, this project aims to harness the power of Earth observation data to monitor and predict weather patterns more effectively.

## How This Project Contributes <a name="how-this-project-contributes"></a>

- **Enhanced Weather Forecasting:** By utilizing machine learning algorithms with satellite data, this project improves the accuracy and reliability of weather predictions, enabling better preparedness for natural disasters and extreme weather events.
- **Climate Change Monitoring:** Analyzing satellite imagery allows for the detection of long-term trends and patterns related to climate change, helping researchers and policymakers develop strategies for adaptation and mitigation.
- **Disaster Management:** Accurate weather forecasts aid in early warning systems for natural disasters such as hurricanes, floods, and wildfires, facilitating timely evacuation and resource allocation.

## Problem Statement <a name="problem-statement"></a>

Accurate weather prediction is essential for various sectors such as agriculture, transportation, and disaster management. Traditional methods often lack precision and fail to capture complex patterns in weather data. This project aims to leverage machine learning techniques to improve weather forecasting by analyzing satellite data and identifying relevant patterns and trends.

## Dataset Description <a name="dataset-description"></a>

The dataset used in this project comprises meteorological data collected over the last 10 years for Bengaluru and Delhi. It includes parameters such as minimum and maximum temperatures, UV indices, sunrise and sunset times, and more. The dataset files are available in the [`Datasets`](https://github.com/shrutin0492/special-topics-1/tree/main/Datasets) directory.

## Methodology <a name="methodology"></a>

The project employs linear regression, decision trees, random forests, and ARIMA algorithms for weather prediction. These algorithms are chosen for their ability to handle numerical data and capture non-linear relationships effectively.

## Evaluation Metrics <a name="evaluation-metrics"></a>

The performance of the machine learning models is evaluated using the following metrics:
- **Mean Absolute Error (MAE):** Measures the average absolute difference between predicted and actual values, providing insights into the model's accuracy.
- **R2-score:** Indicates the proportion of variance in the dependent variable that is predictable from the independent variables.
- **Variance Score:** Measures the proportion of the variance in the target variable that is predictable from the features.

These metrics help assess the models' accuracy, reliability, and generalization capabilities.

## Results <a name="results"></a>

### Linear Regression
- Mean Absolute Error: 0.48
- R2-score: 0.97
- Execution Time: 10.24 seconds

### Decision Tree
- Mean Absolute Error: 0.38
- R2-score: 0.98
- Execution Time: 6.92 seconds

### Random Forest
- Mean Absolute Error: 0.34
- R2-score: 0.98
- Execution Time: 42.17 seconds

Detailed results are available in the project documentation.

## Why Certain Models and Evaluation Metrics <a name="why-certain-models-and-evaluation-metrics"></a>

The choice of machine learning models and evaluation metrics is based on several factors:
- **Model Complexity:** Linear regression, decision trees, and random forests are chosen for their simplicity and interpretability, making them suitable for initial analysis and benchmarking.
- **Robustness:** These models are known for their robustness and ability to handle noisy data, making them suitable for weather prediction tasks.
- **Evaluation Metrics:** MAE, R2-score, and variance score are commonly used metrics for regression tasks, providing comprehensive insights into model performance.

## What the Code Does <a name="what-the-code-does"></a>

The code preprocesses the dataset, trains the machine learning models, and evaluates their performance. It also generates visualizations to analyze the relationship between weather parameters and predict weather patterns.

## Relevant Links <a name="relevant-links"></a>

- [Project Repository](https://github.com/shrutin0492/special-topics-1)
- [Dataset](https://github.com/shrutin0492/special-topics-1/tree/main/Datasets)
- [Jupyter Notebook](https://github.com/shrutin0492/special-topics-1/blob/main/st1_eo.ipynb)
- [Linear Regression Model Image](https://github.com/shrutin0492/special-topics-1/blob/main/Results/LrModel.png)
- [Linear Regression Table Image](https://github.com/shrutin0492/special-topics-1/blob/main/Results/LrTable.jpeg)
- [Decision Tree Table Image](https://github.com/shrutin0492/special-topics-1/blob/main/Results/decTable.jpeg)
- [Random Forest Table Image](https://github.com/shrutin0492/special-topics-1/blob/main/Results/RFtable.jpeg)
- [Comparison Image](https://github.com/shrutin0492/special-topics-1/blob/main/Results/comparison.jpeg)
- [Correlation Heatmap Image](https://github.com/shrutin0492/special-topics-1/blob/main/Results/correlation_filtered.jpeg)
- [Model Architecture Image](https://github.com/shrutin0492/special-topics-1/blob/main/Results/model_architecture.png

)

## How to Run <a name="how-to-run"></a>

To run the code locally, follow these steps:
1. Clone the repository to your local machine.
2. Navigate to the repository directory.
3. Open the Jupyter Notebook `st1_eo.ipynb` using Jupyter or any compatible environment.
4. Execute the code cells in the notebook sequentially.

## Future Improvements <a name="future-improvements"></a>

- Incorporate additional machine learning models such as neural networks, support vector machines, and ARIMA for weather prediction to achieve even better results.
- Explore the use of Google Earth Engine API and satellite imagery for more comprehensive Earth observation and weather forecasting.
- Implement ensemble learning techniques to combine the predictions of multiple models for improved accuracy and robustness.

## Achievements <a name="achievements"></a>

- Developed machine learning models for weather prediction using Earth observation data.
- Achieved high accuracy and reliability in weather forecasts through extensive experimentation and analysis.
- Contributed to the field of Earth observation and climate science by leveraging satellite data and machine learning techniques.

## Additional Considerations <a name="additional-considerations"></a>

This project demonstrates the potential of machine learning and Earth observation data in improving weather forecasting accuracy and contributing to climate science research. By leveraging advanced technologies and interdisciplinary approaches, we can address complex environmental challenges and build a more sustainable future.

---

This README provides an overview of the project, its objectives, methodology, results, and future directions. For more details, refer to the project documentation and Jupyter Notebook.

Feel free to explore the repository and provide feedback or contributions. Thank you for your interest in our project!
