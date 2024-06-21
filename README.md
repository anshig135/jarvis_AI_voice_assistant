

# Jarvis A.I. :- Voice Assistant 🎤🤖

Jarvis A.I. is a Python-based voice assistant that leverages OpenAI's language models to provide interactive and intelligent responses. It is designed to perform various tasks such as opening websites, playing music, providing the current time, and executing custom commands based on user inputs. Jarvis A.I. can also save responses from OpenAI to a text file for later reference.



## Tech Stack

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
## Features

* Voice Recognition: Uses Google's Speech Recognition API to convert spoken words into text.
* Text-to-Speech: Utilizes the built-in say command on macOS to convert text responses into spoken words.
* OpenAI Integration: Connects to OpenAI's API to generate intelligent responses to user queries.

* Custom Commands:
    * Open popular websites like YouTube, Wikipedia, and Google.
    * Play a specific music file.
    * Provide the current time.
    * Open system applications like FaceTime and Passky.
    * Save AI Responses: Saves responses from OpenAI to a text file for future reference.
* Chat History: Maintains a chat history for context in conversations.


## Installation

* Clone the Repository

```bash
 git clone https://github.com/yourusername/jarvis-ai.git
 cd jarvis-ai

```

* Install Dependencies

```bash
  pip install -r requirements.txt

```

* Configuration:

    Create a config.py file in the project directory and   add your OpenAI API key:

```bash
  apikey = 'your-openai-api-key'
```
    
## Usage

* Run the Voice Assistant

```bash
 python jarvis.py
```

* Interact with Jarvis:

    * Speak commands such as "Open YouTube", "What is the time?", "Using artificial intelligence, explain machine learning", etc.
    * Jarvis will respond to your commands and provide spoken feedback.

* Supported Commands:

    * Open websites: "Open YouTube", "Open Wikipedia", "Open Google".
    * Play music: "Open music".
    * Get current time: "What is the time?".
    * Open applications: "Open FaceTime", "Open Passky".
    * AI prompt: "Using artificial intelligence, [your query]".
    * Exit program: "Jarvis Quit".
    * Reset chat history: "Reset chat".


## Adding More Features

To add more features, you can modify the main loop in the jarvis.py file. Add more conditions to handle different voice commands and implement the corresponding actions.
## Contributing

Feel free to fork this repository, create new features, fix bugs, or improve the existing code. Pull requests are welcome!
