# Loan Prediction Approval Project

## Overview

The Loan Prediction Approval project is a machine learning application designed to predict whether a loan application will be approved or rejected based on various input features. This project leverages data science and machine learning algorithms to assist financial institutions in making informed decisions about loan approvals.

## Features

- Predicts loan approval status (Approved/Rejected) based on input features.
- Uses historical loan application data to train the model.
- Provides insights into feature importance for decision-making.

## Technologies Used

- **Programming Language:** Python
- **Libraries:** 
  - `pandas` for data manipulation
  - `numpy` for numerical operations
  - `scikit-learn` for machine learning models
  - `matplotlib` and `seaborn` for data visualization
- **Machine Learning Models:** Logistic Regression, Random Forest, Gradient Boosting (or any other models used)


## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/manne.namratha/loan-prediction.git
   cd loan-prediction
   ```

2. **Create a Virtual Environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Download the Dataset:**

   Ensure you have the dataset in the correct path. Update the `data_path` variable in `config.py` if necessary.

## Usage

1. **Prepare Data:**

   Ensure the dataset is in the correct format and located in the `data/` directory.

2. **Train the Model:**

   Run the training script to train the model with the provided dataset.

   ```bash
   python train_model.py
   ```

3. **Make Predictions:**

   Use the prediction script to make predictions on new data.

   ```bash
   python predict.py --input data/new_application.csv
   ```

4. **Evaluate the Model:**

   Evaluate the performance of the model on test data.

   ```bash
   python evaluate_model.py
   ```

## Configuration

Update the `config.py` file to configure paths and model parameters:

- `DATA_PATH` - Path to the dataset
- `MODEL_PATH` - Path to save/load the model
- `FEATURE_COLUMNS` - List of features used for training

## Testing

Run tests to ensure the application is working as expected:

```bash
pytest
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request


## Contact

For questions or suggestions, please contact:

- **Email:** manne.namrathasai@gmail.com

