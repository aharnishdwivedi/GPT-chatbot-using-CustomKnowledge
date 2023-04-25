# GPT-chatbot-using-CustomKnowledge

This is a simple psychological chatbot built using OpenAI's GPT-3.5 language model. The chatbot is designed to respond to text input and provide helpful and supportive responses to users.

Installation
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/<username>/<repository-name>.git
Install the required packages using pip:

Copy code
pip install -r requirements.txt
Set your OpenAI API key in the environment variable OPENAI_API_KEY. You can obtain your API key by creating an account on OpenAI's website.

Usage
To launch the chatbot interface, run the following command:

Copy code
python app.py
This will start the Gradio interface where you can enter text input and receive responses from the chatbot.

You can also customize the chatbot by modifying the construct_index function in app.py. This function is responsible for creating the GPTSimpleVectorIndex that the chatbot uses to generate responses.

Contributing
Contributions are welcome! If you find a bug or have a suggestion for a new feature, please open an issue or submit a pull request.
