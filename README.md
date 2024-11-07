Simple Python Chatbot
This repository contains a basic chatbot implemented in Python, using simple pattern-matching to respond to user input. This project demonstrates how to use regular expressions and probability scoring to analyze text and generate responses.

Features
Responds to various greetings, farewells, and questions.
Uses keyword matching and response probability scoring.
Returns default responses when input is not recognized.
Code Overview
get_response(user_input): Processes user input and generates an appropriate response.
message_probability: Calculates the likelihood of a response based on recognized keywords.
check_all_messages: Checks and compares the probability scores for possible responses.
unknown: Generates a default response if the input is not recognized.
How to Run
Clone this repository:

bash
Copy code
git clone https://github.com/yourusername/simple-python-chatbot.git
Run the script:

bash
Copy code
python chatbot.py
Interact with the bot by typing messages. Type quit to exit.

Example Usage
plaintext
Copy code
Bot: Hello! I'm a simple chatbot. Type 'quit' to exit.
You: Hello
Bot: Hello!
You: How are you?
Bot: I'm doing fine, and you?
License
This project is licensed under the MIT License.

