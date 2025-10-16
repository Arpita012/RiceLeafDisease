# Rasa Chatbot Project

Welcome to the Rasa Chatbot project! This repository contains the implementation of a chatbot using the Rasa framework.

## Getting Started

Follow these steps to set up and run the Rasa chatbot:

### Train Natural Language Understanding (NLU):

`$ rasa train nlu`

Train the Natural Language Understanding (NLU) component to enhance the chatbot's understanding of user input.

### Train Full Model:

`$ rasa train`

Train the complete Rasa model, including both NLU and dialogue management, ensuring a comprehensive chatbot training.

### Run Rasa actions:

`$ rasa run actions`

To start the custom actions

### Run Rasa Server with API:

`$ rasa run --enable-api --cors "*" `

Start the Rasa server with an enabled API, allowing seamless integration with external systems and enabling Cross-Origin Resource Sharing (CORS) from any origin.
