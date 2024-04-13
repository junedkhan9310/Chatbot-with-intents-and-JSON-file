# Natural Language Processing (NLP) Chatbot

## Overview

This project implements a chatbot using natural language processing (NLP) techniques. The chatbot is trained to understand and respond to user input by utilizing the NLTK library for text processing and TensorFlow for building a neural network model. The main objective is to create a conversational interface that can engage with users and provide relevant responses.

## Requirements

To run this project, you will need:

- Python 3.x
- Required libraries: `nltk`, `tflearn`, `tensorflow`

You can install the necessary libraries using pip:

```bash
pip install nltk tflearn tensorflow
```

## Usage

1. Clone this repository to your local machine.

```bash
git clone <repository_url>
```

2. Navigate to the project directory.

```bash
cd <project_directory>
```

3. Run the main script to train the chatbot and start the conversation.

```bash
python chatbot.py
```

## Implementation Details

### Text Preprocessing

- The NLTK library is used for text preprocessing tasks such as tokenization and stemming.
- LancasterStemmer from NLTK is employed to reduce words to their root form.

### Neural Network Model

- TensorFlow and tflearn are utilized to build a neural network model for the chatbot.
- The model is trained on the provided intents data to understand user queries and generate appropriate responses.

### Data Loading

- The intents data is loaded from a JSON file named `intents.json`.
- This file contains various intents along with their associated patterns and responses.

## File Structure

- `chatbot.py`: Main script containing the implementation of the chatbot.
- `intents.json`: JSON file containing the intents data.
- `README.md`: This file providing an overview of the project.

## Contributors

- [Khan Juned](https://github.com/junedkhan9310) - Project Developer
