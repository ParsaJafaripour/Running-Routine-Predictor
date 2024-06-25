# Running Routine Predictor

A machine learning project to predict personalized running routines based on past running data. This project leverages Python, TensorFlow/Keras, pandas, and scikit-learn for data preprocessing, feature engineering, model training, and evaluation.

## Project Overview

The goal of this project is to help runners get back into their groove efficiently after a break by predicting the best running routine based on previous running data.

## Files in the Repository

- `main.ipynb`: The main Jupyter Notebook containing the project code.
- `running_model.keras`: The saved Keras model file.
- `scaler.pkl`: The saved scaler used for data preprocessing.
- `cleaned_running_data.csv`: The cleaned running data.
- `augmented_running_data.csv`: The augmented running data.
- `feature_engineered_running_data.csv`: The feature engineered running data.

## Key Features

- **Data Preprocessing and Feature Engineering**
  - Cleaning and transforming the raw running data.
  - Creating new features like rolling averages and time since last run.

- **Model Training**
  - Building and training a neural network using TensorFlow/Keras.
  - Synthetic data generation for data augmentation to improve model performance.

- **Model Evaluation**
  - Evaluating the model's performance using metrics like Mean Squared Error and R-squared.

## Usage

1. **Clone the Repository:**

    ```sh
    git clone https://github.com/yourusername/Running-Routine-Predictor.git
    cd Running-Routine-Predictor
    ```

2. **Install Dependencies:**

    Install the required Python packages (it's recommended to use a virtual environment):

    ```sh
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebook:**

    Open and run `main.ipynb` to see the data preprocessing, model training, and evaluation steps.

4. **Predict New Running Routine:**

    Use the provided code to predict a new running routine based on input parameters (current fitness level, duration of the break, etc.).

## Results

The final model achieved a mean squared error of 0.113 and an R-squared value of 0.936, indicating a high level of accuracy in predicting the recommended running distance.

## Contributing

Feel free to fork this repository and contribute by submitting pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
