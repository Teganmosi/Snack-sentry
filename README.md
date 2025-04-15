# Snack Sentry 🍔🍕

A machine learning project that predicts snack preferences based on mood, time of day, hunger level, sentiment, snack type, and texture. It features a mix of Nigerian snacks (e.g., suya, puff puff, chin chin) and common snacks (e.g., chips, chocolate), using a Random Forest Classifier to recommend snacks tailored to your mood and context.

## Features
- Generates a synthetic dataset of 1800 samples with mood-snack affinities.
- Trains a Random Forest Classifier to predict snack groups (e.g., Nigerian fried, savory snacks, healthy light).
- Provides an interactive CLI to input mood, time, and preferences for personalized snack recommendations.
- Visualizes snack group trends, feature importance, and model performance (confusion matrix).
- Saves the dataset as `snack_data.csv` for further analysis.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/snack-sentry.git
   cd snack-sentry

## Set up a virtual environment (optional but recommended):
    ```bash
    python -m venv .venv
    source .venv/bin/activate  # On Windows: .venv\Scripts\activate





## Install dependencies:
    ```bash

      pip install -r requirements.txt

### Usage
Run the script to generate the dataset, train the model, and start the interactive predictor:
    ```bash

    python app.py


Follow the prompts to enter:
Your mood (e.g., happy, stressed, hungry)

Time of day (morning, afternoon, evening, midnight)

Hunger level (0 to 1)

Sentiment (-1 to 1)

Preferred snack type (sweet, savory, spicy, light)


## Model Details
Algorithm: Random Forest Classifier with grid search for hyperparameter tuning.

Features: Mood, time of day, hunger level, sentiment, snack type, snack texture.

Output: Predicted snack group, with a weighted random selection of a specific snack.

Performance: Evaluated using accuracy, cross-validation, and a classification report.


## Contributing
Contributions are welcome! Please:
Fork the repository.

Create a feature branch (git checkout -b feature/your-feature).

Commit changes (git commit -m "Add your feature").

Push to the branch (git push origin feature/your-feature).

Open a pull request.

## License
MIT License (LICENSE)
## Contact
For questions or feedback, open an issue or reach out.











