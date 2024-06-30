## Live Project - https://mediwise.onrender.com
(Kindly wait some time for getting the project to load)

# MediWise Web Application

This web application provides medical insights based on user-input symptoms. It utilizes a machine learning model trained on medical datasets to provide accurate predictions along with relevant medical information.user can also find list of symptoms from Symptoms page.

## Features

- **Symptom-based Disease Prediction**: Users input their symptoms, and the application predicts potential diseases using a Support Vector Classifier (SVC) model.
  
- **Comprehensive Disease Information**: For the predicted disease, the application provides:
  - **Description**: Detailed description of the disease.
  - **Precautions**: Recommended precautions to manage or prevent the disease.
  - **Medication**: List of medications commonly prescribed for the disease.
  - **Workout**: Suitable exercises or physical activities for managing the disease.
  - **Diet**: Dietary recommendations for individuals diagnosed with the disease.
  
- **User-friendly Interface**: The interface is designed to be intuitive, allowing users to easily enter symptoms and receive detailed disease information.
- **Symptoms Page**: Users can also explore a comprehensive list of symptoms to facilitate accurate input.

## Machine Learning Approach
- Supervised Learning: The model was trained with a 70% training and 30% testing split on labeled medical datasets. This approach ensures robust prediction capabilities based on learned patterns from labeled symptom-disease relationships.

## Tech Stack

- **Backend**: Python, Flask
- **Machine Learning**: SVC model for disease prediction
- **Frontend**: HTML, CSS, Jinja2 templating
- **Data Handling**: Pandas for data manipulation
- **Deployment**: Deployed on Render, ensuring accessibility and reliability

## Dataset

The application is powered by medical datasets including symptom descriptions, disease precautions, medication details, workout recommendations, and dietary guidelines. These datasets are crucial for accurate disease prediction and comprehensive information retrieval.

## Usage

1. **Enter Symptoms**: On the home page, input symptoms separated by commas.
2. **Get Prediction**: Click on the "Predict" button to see the predicted disease and associated details.
3. **Explore Information**: Learn more about the disease including its description, precautions, medications, workouts, and dietary advice.

## Deployment

The application is deployed on Render for seamless access. It ensures the application is available online for users to predict diseases and access medical insights conveniently.

## Contributing

Contributions are welcome! Feel free to fork the repository, make improvements, and submit pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
