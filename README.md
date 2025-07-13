# Emotion-based-music-recommendation-system
This web-based application, developed using Python, uses OpenCV to first detect and analyze the user's current facial emotion in real time. Once a face is detected within the camera frame, the application crops the face from the image and passes it to a trained machine learning model to predict the emotion.
This process is repeated 30 to 40 times over a span of 2–3 seconds, generating a list of detected emotions (which may include duplicates). The application then analyzes the frequency of each emotion, sorts them in descending order, and removes duplicates, resulting in a prioritized list of the user’s emotions.
Finally, the application iterates through this sorted list to recommend songs that match each emotion, providing a personalized music experience based on real-time emotional feedback.

## Installation & Running the App
Create a New Project
Open PyCharm and create a new project. Add all the necessary files (including app.py, requirements.txt, and other code files) to the project directory.

## Install Dependencies
Open the terminal inside PyCharm and run the following command to install all required packages:
pip install -r requirements.txt

##Run the Application
Once the installation is complete, start the app by running:
streamlit run app.py

## Libraries
- Streamlit
- Opencv
- Numpy
- Pandas
- Tensorflow
- Keras


