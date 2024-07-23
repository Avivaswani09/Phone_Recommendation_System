# Phone Recommendation System

This repository contains a project focused on building a phone recommendation system using machine learning techniques. The project involves data preprocessing, feature engineering, and the development of recommendation models using Random Forest and XGBoost algorithms. Additionally, a manual recommendation system is also implemented for comparison.

## Table of Contents
- [Project Overview](#project-overview)
- [Directory Structure](#directory-structure)
- [Data Preprocessing](#data-preprocessing)
- [Recommendation Models](#recommendation-models)
  - [Random Forest](#random-forest)
  - [XGBoost](#xgboost)
  - [Manual Recommendation](#manual-recommendation)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
The primary objective of this project is to develop an efficient and accurate phone recommendation system. The system leverages machine learning algorithms to suggest phones to users based on various features and user preferences.

## Directory Structure
```
├── phone_data_cleaned.csv             # Cleaned dataset
├── Phone_Preprocessing.ipynb          # Data preprocessing notebook
├── Recom_ML_RF.ipynb                  # Random Forest recommendation model notebook
├── Recom_XBoost.ipynb                 # XGBoost recommendation model notebook
├── Recommendation_Manual.ipynb        # Manual recommendation system notebook
├── README.md                          # Project README file
```

## Data Preprocessing (Jupyter NOtebook NumPy and Pandas)
The data preprocessing step involves cleaning and transforming the raw data to make it suitable for machine learning models. The preprocessing steps are documented in the `Phone_Preprocessing.ipynb` notebook.

## Recommendation Models
### Random Forest
The Random Forest model is implemented in the `Recom_ML_RF.ipynb` notebook. This model uses an ensemble of decision trees to predict and recommend phones based on user preferences.

### XGBoost
The XGBoost model is implemented in the `Recom_XBoost.ipynb` notebook. XGBoost is a powerful gradient boosting algorithm that is used to improve the accuracy of the recommendations.

### Manual Recommendation
The manual recommendation system is implemented in the `Recommendation_Manual.ipynb` notebook. This system provides recommendations based on predefined rules and user inputs.

## Installation
To run the notebooks, you need to have Python and Jupyter Notebook installed. You can install the required dependencies using the following commands:

```bash
pip install -r requirements.txt
```

**Note**: Make sure to create a `requirements.txt` file with all necessary packages.

## Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/phone-recommendation-system.git
    ```
2. Navigate to the project directory:
    ```bash
    cd phone-recommendation-system
    ```
3. Open Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
4. Run the notebooks in the following order:
    - `Phone_Preprocessing.ipynb`
    - `Recom_ML_RF.ipynb`
    - `Recom_XBoost.ipynb`
    - `Recommendation_Manual.ipynb`

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
