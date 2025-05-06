# Streamlit-Spam-Detection-App
Spam Detection SystemThis project implements a simple web-based Spam Detection System using Python, scikit-learn, and Streamlit. It allows users to input a message or email and predicts whether it is "spam" or "ham" (not spam).FeaturesLoads a dataset of SMS messages and their labels (spam/ham).Uses the CountVectorizer to convert text data into numerical features.Trains a Multinomial Naive Bayes classifier on the data.Provides a simple Streamlit interface for users to test the model with their own messages.PrerequisitesBefore running this application, ensure you have the following installed:Python 3.6 or higherpandasnumpyscikit-learnstreamlitYou can install these libraries using pip:pip install pandas numpy scikit-learn streamlit
InstallationClone this repository to your local machine:git clone <repository_url>
cd <repository_name>
Save the provided Python code (from the "Streamlit Spam Detection App" Canvas) into a file named app.py (or any other .py file name) in the cloned repository directory.UsageOpen your terminal or command prompt.Navigate to the directory where you saved the app.py file.Run the Streamlit application using the following command:streamlit run app.py
This command will start a local web server, and your default web browser will open a new tab with the Spam Detection System application.Enter a message or email in the text area provided and see the prediction result ("ham" or "spam").Project Structure.
├── app.py          # Main Streamlit application code
└── README.md       # This file
ContributingFeel free to fork this repository, make improvements, and submit pull requests.LicenseThis project is open source and available under the [Specify License, e.g., MIT, Apache 2.0].
