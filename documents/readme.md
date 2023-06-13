## Rasa Chatbot 

This project is based on RASA which is an open source conversational AI framework with additional analytics, security, and observability capabilities.

To install RASA Open source follow this link -

[RASA Open sourse Installation](https://rasa.com/docs/rasa/installation/installing-rasa-open-source)


You can also go through RASA playground before installing it to your system

[RASA Playground](https://rasa.com/docs/rasa/playground/)

To run this project first install rasa then follow these below commands

`rasa train`

This command will train the NLU (Natural Language Understanding) model and the dialogue management model based on the data provided in your project's data directory.

`rasa run -m models --enable-api --cors "*"`


This command starts the Rasa server, loads the trained model from the models directory, enables the API to interact with the chatbot, and allows cross-origin resource sharing (CORS) for handling requests from different domains.