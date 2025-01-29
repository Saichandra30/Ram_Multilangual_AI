# Ram_Multilangual_AI
The Multilingual AI Assistant is a voice-driven personal assistant powered by various libraries like Speech Recognition, Text-to-Speech (TTS), and Google Gemini API for generating content. The assistant can perform tasks such as fetching the time, searching Wikipedia, and opening websites like Google. The project also integrates Streamlit for creating a user-friendly web interface.

**Requirements**

To run the assistant locally, make sure you have the following libraries installed:

- SpeechRecognition,
- pyttsx3,
- gTTS,
- Streamlit,
- wikipedia,
- webbrowser,
- genai (Google Gemini API).

Install the required libraries using pip:

pip install SpeechRecognition pyttsx3 gTTS streamlit wikipedia genai

Run the Streamlit app:

streamlit run app.py
After running the app, a web page will open in your default browser where you can interact with the assistant.

**Usage**

Voice Commands:

- Simply click the "Start Listening" button to activate the microphone.
- Speak commands such as "What is the time?", "Open Google", or "Tell me about Python".
- The assistant will respond verbally and show the results on the web page.

Text Input:
- You can also type a command in the text box (on the Streamlit UI) to get a response.

Logging

The application logs interactions and any errors into a file located in the logs directory. This will help debug and track user queries.

Contributing

Feel free to fork the repository and submit pull requests if you have suggestions for improvement or additional features.

**Acknowledgments**

- SpeechRecognition: For voice recognition.
- pyttsx3: For text-to-speech conversion.
- gTTS: For multilingual text-to-speech conversion.
- Streamlit: For creating a web interface.
- Wikipedia API: For fetching Wikipedia summaries.
- Google Gemini API: For generating AI responses.
