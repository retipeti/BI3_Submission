# BI3_Submission
Final submission for Business Intelligence Assignment 3

## Disclaimer - This repository will be public till the last day of February 2026!

## Project Overview

This project analyzes real estate data from Portugal to develop insights and predictive models. The analysis includes data exploration, feature engineering, and machine learning model development, with the full experiment details documented in the final report. 

## Project Structure

- **`src/Realestate_Portugal.ipynb`** - Main Jupyter notebook containing all analysis, visualizations, and model development
- **`data/portugal_listings.csv`** - Dataset containing Portugal real estate listings
- **`data/report/experiment_report.tex`** - Final experiment report with methodology and results
- **`LICENSE`** - MIT License (see [License](#license) section)
- 
## Dataset

This project uses the **portugal_listings.csv** dataset, released under the **MIT License**.

Copyright (c) 2013 Mark Otto  
Copyright (c) 2017 Andrew Fong  
Copyright (c) 2024 Thomas Gaehtgens

Source: <https://www.kaggle.com/datasets/luvathoms/portugal-real-estate-2024/data> (accessed: 2025-12-10)  
License: MIT (see the dataset repository `LICENSE` file)

## Getting Started

### Prerequisites

This project uses **uv** for dependency management. If you don't have it installed, you can install it by following the [official uv documentation](https://docs.astral.sh/uv/).

### Installation

1. Clone or pull this repository
2. Install uv (if not already installed)
3. Run the following command to sync all dependencies:

```bash
uv sync
```

This will install all required packages and create the appropriate virtual environment.

## Running the Project

To run the Jupyter notebook:

```bash
uv run jupyter notebook src/Realestate_Portugal.ipynb
```

Or if you prefer Jupyter Lab:

```bash
uv run jupyter lab src/Realestate_Portugal.ipynb
```

## Dependencies

The project uses the following key libraries:
- **pandas** & **plotly** - Data manipulation and interactive visualizations
- **scikit-learn** - Machine learning algorithms
- **xgboost** - Gradient boosting models
- **matplotlib** & **seaborn** - Static visualizations
- **requests** - HTTP requests for data retrieval
- **ipykernel** - Jupyter kernel support

For a complete list of dependencies, see [`pyproject.toml`](pyproject.toml).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
The original dataset used for this project is licensed under the MIT License, scroll up for further information under the **Dataset** section.
