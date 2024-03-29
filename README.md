# Fertilizer-Prediction


## Overview

This project focuses on predicting the optimal fertilizer type for a given set of soil and crop parameters using machine learning techniques. The goal is to provide recommendations for the most suitable fertilizer to maximize crop yield and improve agricultural practices.



## Background

Understanding the nutrient requirements of crops and soil conditions is crucial for efficient and sustainable agriculture. This project addresses the challenge of recommending the right type of fertilizer based on input parameters such as soil pH, moisture levels, and crop type.

## Features

- **Prediction Model:** Utilizes machine learning algorithms to predict the optimal fertilizer.

## Dependencies

- Python (>=3.6)
- [scikit-learn](https://scikit-learn.org/)
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [xgboost](https://xgboost.readthedocs.io/)
- [catboost](https://catboost.ai/)
- [lightgbm](https://lightgbm.readthedocs.io/)

Install the required dependencies using:

```bash
pip install -r requirements.txt
```

## Installation
Clone the repository:
```bash
git clone https://github.com/yourusername/fertilizer-prediction.git
```

Navigate to the project directory:
```bash
cd fertilizer-prediction
```

Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage 
To run the project:

```bash
python fertilizer-prediction.ipynb
```

This notebook preprocesses the data, trains the model, and saves the trained model as fertilizer.pkl, fertilizer1.pkl, minmax.pkl, and standscaler.pkl for later use.

## Data
The project uses a dataset (Fertilizer Prediction.csv) containing information about soil properties, crop types, and recommended fertilizers. The dataset is available in the data directory.

## Model Training
To train the model, run:

```bash
python fertilizer-prediction.ipynb
```

This notebook preprocesses the data, trains the model, and saves the trained model.


### ***Note:*** The current model may not predict accurately in all scenarios; it is under ongoing refinement and improvement.



## Contributing
Contributions are welcome! Feel free to open issues or pull requests.