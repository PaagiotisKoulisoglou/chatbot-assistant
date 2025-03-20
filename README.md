Chatbot Assistant

A simple AI chatbot built using PyTorch that can be trained with custom intents and responses. It also supports function mappings for executing predefined actions based on recognized intents.

Features

Trainable AI Chatbot: Uses NLP techniques to understand user messages and match them to intents.

Custom Responses: Easily configure intents and responses via a JSON file.

Function Mappings: Execute custom Python functions when certain intents are detected.

Persistent Model: Train, save, and load the model to avoid retraining from scratch.

Installation

Prerequisites

Make sure you have Python installed (>=3.7) along with the required dependencies.

Usage

Training the Chatbot

To train the chatbot with a custom intents.json file, run:

This will process the intents, train the model, and save it for later use.

Running the Chatbot

Once trained, you can load the model and start interacting with it:

Then simply enter your messages, and the chatbot will respond. Type /quit to exit.

Example Intents Format

Modify intents.json to define your own intents and responses:

Custom Function Mappings

The chatbot can also trigger Python functions for specific intents. Example:

Saving & Loading the Model

After training, the model can be saved:

To load a saved model:

Future Improvements

Add more advanced NLP techniques for better understanding.

Integrate with a web or messaging API for real-world applications.

Improve training efficiency with more dataset optimizations.

Contributing

Feel free to fork the repo and submit pull requests with improvements!
