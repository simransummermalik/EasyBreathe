# EasyBreathe
The inspiration for EasyBreathe came with a will to demonstrate how novel machine learning algorithms can have practical purposes in our development of environmental technology. Furthermore, it stems from a pressing need to address air pollution’s health and environmental impacts in North Carolina, a state with complex pollution sources and varied air quality. Recognizing that advanced machine learning could offer new insights, we aimed to create a project that demonstrates that environmental health is no exception to the AI/ML revolution we're currently in.

# What it does 
Trained on data collected from 20 different cities in North Carolina, including 3 of those in the RTP, EasyBreathe makes accurate predictions on the AQI and it predicts the Air Quality concern levels based on the U.S. Air Quality Index (https://www.airnow.gov/aqi/aqi-basics/). Mainly geared towards bettering the health awareness of UNC Chapel Hill's students, but applicable to individuals all over North Carolina, this web app utilizes extreme gradient boosting to make intelligent predictions and it even has capabilities to contact users through email!

# How we Built it
We built EasyBreathe using the XGBoost machine learning algorithm for accurate air quality predictions. The frontend was developed with React.js, while Flask served as the backend web framework to seamlessly connect the different components. We used a MySQL database to handle our data storage. To enhance the data visualization, we incorporated the Google Earth API, enabling live satellite imagery for real-time environmental insights.
Clone the repository to a directory in your system. Run "main.py" using a virtual environment (preferably the virtualenv Python library) with all the packages found in "requirements.txt"

To install the necessary files, activate the virtual environment by running:

MacOS: "source .venv/bin/activate"
Windows: "./venv/Scripts/activate"

and then: "pip install -r requirements.txt"


Sources:
https://app.mailslurp.com/dashboard/ MailSlurp API for emails
https://flask.palletsprojects.com/en/stable/ Flask API framework
Used React and Vite for Front End
Used Pickle to save Machine Learning Model
Google Map API for the map
Used pyMySql in order to connect to sql database in python


AI Usage:
Used AI for advanced debugging, getting exact longitdude and latitdue values for cities, testing mailslurp to ensure the inbox worked, extraplating data to create more blind data for prediciton making

