# Intent-Based Chatbot

## Description

This repository contains the code for an intent-based chatbot built using Natural Language Processing (NLP) and machine learning techniques. The chatbot utilizes a Logistic Regression model to predict the intent of the user's input and provides appropriate responses. It is implemented using Streamlit for the web interface, creating a user-friendly platform for interaction.

## Features

- **Intent Recognition**: Understands and categorizes user inputs into predefined intents.
- **Dynamic Responses**: Generates responses based on the recognized intent.
- **User-Friendly Interface**: Clean and intuitive web interface implemented using Streamlit.
- **Conversation History**: Keeps track of user inputs and chatbot responses in a CSV file.
- **Secure and Efficient**: Implements secure transactions and efficient processing.

## Technologies Used

- **Natural Language Processing (NLP)**: For processing and understanding user inputs.
- **Logistic Regression**: A machine learning algorithm used to classify intents.
- **Streamlit**: For creating and deploying the web interface.
- **Python**: Primary programming language used.
- **TF-IDF Vectorizer**: For converting text data into numerical format.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/intent-based-chatbot.git
    ```

2. Navigate to the project directory:
    ```sh
    cd intent-based-chatbot
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

4. Run the Streamlit application:
    ```sh
    streamlit run app.py
    ```

## Usage

- **Home Page**: Enter your message in the text input box and receive a response from the chatbot.
- **Conversation History**: View past interactions stored in the chat_log.csv file.
- **About Page**: Learn more about the chatbot, its features, and the technologies used.

## File Structure

```
intent-based-chatbot/
├── intents.json          # Intent patterns and responses
├── app.py                # Main application code
├── requirements.txt      # Dependencies
├── chat_log.csv          # Log file for storing conversations
├── style.css             # External CSS for styling (if used)
├── images/
│   ├── image.webp        # Main image for the chatbot interface
│   ├── background.png    # Background image for the chatbot interface
└── README.md             # Project documentation
```

## Future Enhancements

- Incorporate more advanced machine learning models.
- Expand the dataset to handle more complex queries.
- Add new features to enhance user interaction and experience.

## Contact

If you have any feedback or questions, feel free to reach out to us. We are always looking to improve and appreciate your input.

Thank you for using our Intent-Based Chatbot. We hope it makes your experience enjoyable and efficient!

##Test it here 
- https://arjavjain5203-nlp-based-chat-bot-chatbot-turf5s.streamlit.app/