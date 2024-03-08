# Chat GPT Recommendation System

This project utilizes OpenAI's GPT-3.5-turbo model to provide recommendations based on user input. It's a simple implementation that showcases how to interact with the OpenAI API using Python.

## Installation

Before running the script, you need to install the `openai` Python package. You can do this by running the following command:

```bash
!pip install openai==0.28
```
## Usage
To use this script, you need to set up your OpenAI API key. Replace the placeholder in the code with your actual API key.

openai.api_key = 'your-api-key'

The main function chat_gpt_recommendation takes a string input and returns a response from the GPT-3.5-turbo model.

#Example:

input = "What is the capital of India?"
print(chat_gpt_recommendation(input=input))

## Disclaimer
Please ensure that you do not expose your API key publicly. Always keep it secure and confidential.

## License
This project is open-sourced under the MIT license.


Please make sure to replace `<key>` with your actual OpenAI API key and keep it confidential to prevent unauthorized usage.

Also, note that the `!pip install` command is typically used in Jupyter notebooks. If you're running the script in a different environment, you might want to use `pip install openai==0.28` instead.
