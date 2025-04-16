# Q-A

# GenAI Bot using Google PaLM API

This project is a Generative AI-powered chatbot built using Google's PaLM API. The bot is capable of processing natural language queries and generating human-like responses. 

## Features
- Integration with Google PaLM API for text generation.
- Customizable prompts for various applications.
- Supports real-time interaction via a chatbot interface.
- Scalable and easy to deploy.

## Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/genai-bot.git
   cd genai-bot
   ```

2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

3. Set up your API key:
   - Obtain your Google PaLM API key from the Google Cloud console.
   - Create a `.env` file and add the following:
     ```sh
     PALM_API_KEY=your_api_key_here
     ```

## Usage

Run the bot:
```sh
python main.py
```

## Configuration

Modify the `config.py` file to customize bot behavior.

## Deployment

You can deploy this bot using platforms like AWS, GCP, or a simple Flask API.

## License

This project is licensed under the MIT License.
