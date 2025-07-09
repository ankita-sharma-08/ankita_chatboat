# ankita_chatboat
Link for the chat bot
* https://ankitachatboat-doctor.streamlit.app/
## Overview
The Health Symptom Checker is a web application built using Streamlit and OpenAI's GPT-3.5-turbo model. This app allows users to describe their health symptoms and receive general remedies or advice based on their input.

## Features
* User Input: Users can describe their symptoms through a chat interface.
* Chat History: The app maintains a history of the conversation, displaying both user inputs and assistant responses.
* Health Advice: The app utilizes OpenAI's language model to provide general health advice based on the symptoms described by the user.
## Requirements
To run this application, you need the following:

* Python 3.7 or higher
* Streamlit
* OpenAI Python client

## Code Structure
streamlit_app.py: The main application file containing the logic for user input, chat history, and interaction with the OpenAI API.
## Key Components
* OpenAI Client Initialization: The app initializes the OpenAI client using the API key stored in Streamlit's secrets.
* Session State: The app uses Streamlit's session state to keep track of the chat history.
* User Input Handling: The app collects user input and processes it to generate a response from the OpenAI model.
* Response Generation: The get_response function sends the user's symptoms to the OpenAI model and retrieves the assistant's advice.
## Usage
* Open the application in your web browser.
* Describe your symptoms in the chat input box.
* Receive health advice from the assistant based on your input.
