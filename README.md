
# Voice-Activated Chatbot with Grammar Checker

This project is a voice-activated chatbot that uses OpenAI's GPT-3 API to generate responses to user input. The chatbot also features a grammar checker that uses the LanguageTool API to highlight any grammatical errors in the conversation.

## Requirements

The following Python packages are required to run this project:

- openai
- pyttsx3
- speech_recognition
- requests

## Usage

1. Ensure that the required packages are installed.
2. Obtain an OpenAI API key and insert it in the `openai.api_key` variable.
3. Run the script.
4. The chatbot will prompt you to speak. Speak into your microphone.
5. The chatbot will generate a response to your input.
6. The response and your input will be written to a file called `conversation.txt`.
7. Once you are finished speaking with the chatbot, say "bye bye" to end the conversation.
8. The grammar checker will automatically run on the `conversation.txt` file once the chatbot is done. The checker will output any grammatical errors found in the conversation.

## Files

- `voice_chatbot.py`: This is the main Python script that contains the chatbot logic.
- `conversation.txt`: This file contains a log of the conversation between the user and the chatbot.
- `README.md`: This file.

## API Keys

- OpenAI API key: Obtain from [OpenAI](https://beta.openai.com/signup/).
- LanguageTool API key: Not required.

## Notes

- The script assumes that your microphone is located at device index 1. If your microphone is located at a different index, change the `device_index` variable in the script accordingly.
- The chatbot's name is "John Cena". You can change this by modifying the `bot_name` variable in the script.
- The chatbot uses the GPT-3 engine with the `text-davinci-003` model. You can change this by modifying the `engine` variable in the script.
- The chatbot currently only supports English input and output.
