# Sales Prediction Using Advertising Expenditure

This project aims to predict the sales a company earns based on its expenditure on various advertising platforms. The model leverages machine learning techniques to analyze the relationship between advertising spend and sales revenue.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In today's competitive market, understanding the impact of advertising on sales is crucial for businesses. This project utilizes historical data to train a predictive model that helps companies optimize their advertising budgets.

## Installation

To get started, clone the repository and install the required packages:

```bash
git clone https://github.com/yourusername/sales-prediction.git
cd sales-prediction
pip install -r requirements.txt
```

## Usage

To run the model, use the following command:

```bash
python main.py
```

You can modify the input parameters in `config.py` to adjust the advertising spend on different platforms.

## Data

The dataset used in this project includes:

- **TV**: Expenditure on TV advertising
- **Radio**: Expenditure on Radio advertising
- **Newspaper**: Expenditure on Newspaper advertising
- **Sales**: Sales revenue generated

The data can be found in the `data/` directory.

## Model

This project implements the following machine learning algorithms:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

You can find the model implementation in the `models/` directory.

## Results

The performance of the model is evaluated using metrics such as Mean Absolute Error (MAE) and R-squared. The results are documented in `results/`.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
