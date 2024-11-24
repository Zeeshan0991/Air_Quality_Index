
# Air Pollution Time-Series Analysis and Prediction

This project focuses on analyzing and predicting air pollutant concentrations, specifically PM2.5 values, using a time-series modeling approach. The dataset is preprocessed to handle missing values, normalized, and prepared for machine learning models.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Features and Methodology](#features-and-methodology)
3. [Installation and Setup](#installation-and-setup)
4. [Usage](#usage)
5. [Technologies Used](#technologies-used)
6. [License](#license)

## Project Overview

The primary objective of this project is to explore and predict pollutant levels using time-series data. The analysis incorporates data preprocessing, visualization, and sequence-based modeling techniques.

## Features and Methodology

- **Data Preprocessing**: 
  - Handling missing values.
  - Normalizing and scaling data.
  - Splitting data into training and testing sets.

- **Exploratory Data Analysis (EDA)**:
  - Visualizing pollutant trends over time.
  - Checking for null values and feature distributions.

- **Time-Series Modeling**:
  - Using sequential models to predict future pollutant concentrations based on historical data.

- **Machine Learning**:
  - Built and trained LSTM models using TensorFlow/Keras.

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone <repository-link>
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Place the dataset (`data.csv`) in the project directory.

4. Run the notebook:
   ```bash
   jupyter notebook "Analysis, visualization and building the model.ipynb"
   ```

## Usage

1. **Load the Data**: The dataset should be in CSV format and contain pollutant concentration data.
2. **Preprocessing**: Execute the cells to handle missing values, normalize data, and prepare sequences.
3. **Model Training**: Train the LSTM model on the prepared time-series data.
4. **Prediction**: Use the trained model to predict future pollutant levels.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - Data Analysis: `Pandas`, `NumPy`
  - Visualization: `Matplotlib`, `Seaborn`
  - Machine Learning: `TensorFlow`, `Keras`, `Scikit-learn`

## License

This project is licensed under the MIT License. See the LICENSE file for details.
