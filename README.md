**Health Care Center
****Overview
**The Health Care Center is a web application designed to help users predict diseases based on their symptoms. It provides information on the predicted disease, its description, precautions, medications, workouts, and diets. The application uses Flask for the backend and Bootstrap for styling.

**Features
**Symptom Input: Users can enter symptoms or use speech recognition to provide symptoms.
Disease Prediction: Predicts possible diseases based on user input.
Modals for Information: Provides detailed information about the disease, including:
Description
Precautions
Medications
Workouts
Diets
Installation
Clone the Repository


git clone https://github.com/Anki-14/Medicine-Recommendation-System.git
cd health-care-center
Set Up a Virtual Environment

python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`
Install Dependencies
pip install -r requirements.txt
Run the Application

flask run
Usage
Open the Application: Navigate to http://127.0.0.1:5000 in your web browser.
Enter Symptoms: Type symptoms into the input field or use the speech recognition button to provide symptoms.
View Results: After submission, view the predicted disease and detailed information in the modals.
Contributing
Feel free to submit issues or pull requests to improve the application.
