# Automated Skin Disease Detection System

## Project Title
Automated Skin Disease Detection System

## Description
This project aims to provide an accessible and accurate method for diagnosing skin diseases through digital images. By utilizing state-of-the-art image classification techniques, such as the VGG16 model, our system allows users to capture images of their skin conditions and receive immediate analysis and diagnosis. The system is designed to enhance access to healthcare, provide timely diagnosis and treatment, and offer a high degree of accuracy and reliability in identifying various skin conditions.

Our solution not only detects and categorizes skin problems but also predicts the severity level of the disease. The system's distinct feature is its ability to offer users the option to consult a dermatologist remotely, ensuring the accuracy of the diagnosis. This feature enhances trust and confidence in our automated diagnosis system.

## Features
- **Image Acquisition:** Users can capture digital images of affected skin areas using any standard camera.
- **Image Analysis:** The system processes the images using the VGG16 model and applies image processing techniques to identify the type of skin disease.
- **Presentation of Results:** Results, including the identified disease type, are presented to the user in a user-friendly manner.
- **Verification Process:** Users can opt for a verification process, where the image and prediction are reviewed by a dermatologist within a few days.
- **Severity Prediction:** The system predicts the severity level of the detected skin disease to provide users with a comprehensive diagnosis.

### Prerequisites
Ensure the following are installed:

- Python 3.x
- **Flask**: pip install Flask
- **TensorFlow**: pip install tensorflow
- **MySQL**: MySQL server and pip install mysql-connector-python
- **Pillow**: pip install pillow
- 
## Usage

### Input
- Users upload an image of the affected skin area through the system's web interface.
- The image is processed and analyzed to identify potential skin diseases.

### Output
- The system provides an immediate diagnosis, displaying the identified disease and predicted severity level.
- Users can also submit the diagnosis for verification by a dermatologist.

## Files Overview

### `styles.css`
Defines the visual styling for the web application, including layout, colors, and typography. The design focuses on a clean, user-friendly interface with intuitive navigation and accessible features.

### `sign.css`
Handles the styling of the sign-in and sign-up forms, ensuring a consistent and aesthetically pleasing user experience across all authentication pages.

### `result.css`
Responsible for the styling of the results page, where the analysis is displayed. The design ensures clear and easy-to-read results, with centered headings, informative paragraphs, and prominent buttons.

### `main.py`
This is the core backend script for handling database operations and managing user data. Key functions include:
- Creating tables in the MySQL database.
- Populating sample data for testing.
- Checking and verifying login credentials.
- Handling image retrieval and conversion for doctor analysis.
- Managing the workflow of image submission and doctor assignment.

## Contributors
- Lavanya Vasudevan ( LaviVasudevan )
- Aashika Jetti
- Karpagavalli S
