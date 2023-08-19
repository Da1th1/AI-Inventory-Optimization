 # Inventory Optimization using Machine Learning

## Overview
This repository contains a Python-based solution for optimizing inventory levels using historical sales and inventory data. The project aims to predict when and how much of a product to reorder to minimize costs and avoid stockouts.

## Table of Contents
- [Inventory Optimization using Machine Learning](#inventory-optimization-using-machine-learning)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [Dataset](#dataset)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [Results](#results)
  - [Contributing](#contributing)
  - [License](#license)

## Dataset
The data used in this project is stored in `inventory_data.csv`. It contains columns for dates, sales figures, and inventory levels for different products.

## Getting Started

### Prerequisites
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Installation  

1. Clone this repository:

```git clone https://github.com/Da1th1/AI-Inventory-Optimization.git```  
  

## Results
The model predicts future sales using historical sales data and inventory levels. The evaluation metrics obtained are:
- Mean Absolute Error (MAE): 0.56
- Root Mean Squared Error (RMSE): 0.83

These metrics provide insights into the model's accuracy in predicting sales.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License. See `LICENSE` for more details.

