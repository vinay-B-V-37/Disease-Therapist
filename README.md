# Disease-Therapist

# Disease Predictor System

This repository contains code for a Disease Predictor System implemented in Python. The system utilizes machine learning algorithms to predict the disease based on the symptoms provided by the user.

## Problem Statement 
Getting a consultation with a doctor for predicting a disease is a time-consuming task. At the same time, relying on self-diagnosis without consulting a doctor can be risky. 


## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Implementation Diagram](#Implementation)
- [Output](#output)
- [Contributing](#contributing)

## Introduction

The Disease Predictor System is designed to provide expert medical advice to users by predicting the disease based on the symptoms entered. The system uses two machine learning algorithms, namely Decision Tree and Random Forest, to classify the disease based on the symptoms.

The system is built using the following libraries and technologies:

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Tkinter (GUI framework)

The system reads the training data from a CSV file and preprocesses it to prepare the data for training the machine learning models. It then provides a graphical user interface (GUI) where the user can enter their name and select symptoms from dropdown menus. After submitting the symptoms, the system predicts the most likely disease using the trained models and displays the result to the user.

## Installation

To run the Disease Predictor System, follow these steps:

1. Clone the repository to your local machine.
2. Make sure you have Python installed (version 3.7 or above).
3. Install the required dependencies by running the following command:
   ```
   pip install -r requirements.txt
   ```

## Usage

To use the Disease Predictor System, execute the following steps:

1. Open a terminal or command prompt.
2. Navigate to the cloned repository directory.
3. Run the following command to start the application:
   ```
   python disease_predictor.py
   ```
4. The GUI window of the application will open.
5. Enter your name in the "Applicant Name" field.
6. Select symptoms from the dropdown menus (at least two symptoms).
7. Click the "Decision Tree" or "Random Forest" button to predict the disease using the respective algorithm.
8. The predicted disease will be displayed on the screen.



## Implementation Diagram 

![image](https://github.com/vinay-ai-developer/Disease-Therapist/assets/106902815/3f75220d-d8c1-43d0-8b94-70f8898cda55)


## Output 

![image](https://github.com/vinay-ai-developer/Disease-Therapist/assets/106902815/56481dc5-8a23-4736-8dcc-82692cd36f23)


## Future Scope 

Inclusion of a dedicated extension page can offer additional functionalities and predictions related to healthcare. By leveraging generative AI technology and API access, the model can be enhanced to allow users to provide prompts or descriptions of their symptoms directly. This extension page can serve as a comprehensive resource for users, enabling them to access a wide range of health-related predictions and information within a single platform. 


## Contributing

Contributions to the Disease Predictor System are welcome. If you find any bugs, issues, or have suggestions for improvements, please feel free to open an issue or submit a pull request.


