# Mental Health Assistant Chatbot

## Overview
This project is a **Mental Health Assistant Chatbot** powered by the **Llama 2 model** and **Hugging Face's sentiment analysis**. The chatbot is designed to provide personalized emotional support by tracking users' moods and offering appropriate responses based on their emotional state and past interactions.


This tool aims to create a safe space for users to discuss their mental well-being and promote better mental health awareness and practices.

## Features
- **Personalized Greeting**: The chatbot addresses users by their names.
- **Sentiment Analysis**: Tracks and analyzes user sentiment using Hugging Face's sentiment analysis model.
- **Mood & Question Tracking**: Saves user moods and previous questions to a CSV file, allowing for mood continuity across sessions.
- **Supportive Responses**: Responds with motivational and mood-boosting messages based on detected sentiment and using prompt engineering and sentiment analysis.
- **Pre-defined Q&A**: The chatbot refers to a pre-existing CSV-based dataset of questions and answers (`qa_dataset.csv`) to offer immediate responses to commonly asked questions.


### Requirements
- Python 3.x
- Google Colab
- Hugging Face Transformers Library
- Gradio (for user interface)
- pandas (for CSV management)


## Project Structure
- `main.ipynb`: The main Google Colab notebook containing all code for the chatbot.
- `user_moods.csv`: A file that stores user names, moods, and their previous questions across sessions.
- `qa_dataset.csv`: A pre-defined question-answer dataset used by the chatbot to check and respond to frequently asked questions.
- `README.md`: This file, providing an overview of the project and setup instructions.

## CSV Functionality
- **Mood & Question Tracking**: The chatbot stores the user's name, their mood, and the last question they asked in a CSV file (`user_moods.csv`).
- **Pre-defined Q&A**: The chatbot uses `qa_dataset.csv`, which contains frequently asked questions and their corresponding answers. If a user's query matches any in this dataset, the chatbot provides an immediate response.
 
## Colab Notebook Link
The Google Colab notebook can be found [here](https://colab.research.google.com/drive/1Xym0qJZy3jAIihA4DKCPWM3yZEg5lZg2?usp=sharing).

### Setup Instructions

1. Open the notebook link in Google Colab or run it locally.

2. Run the main mental-health-assistant-chatbot.ipynb notebook or script to start the chatbot interface.

