# Conversational_AI

A conversational AI system built with the following key components:

- 1) **Speech-to-Text (STT)** 
- 2) **Text-to-Speech (TTS)** using ElevenLabs
- 3) **LLM Backend**: `meta-llama/Llama-3.2-1B-Instruct` from Hugging Face
- 4) **Session & Memory Management** using User ID
- 5) **Emotion Detection** using `bhadresh-savani/distilbert-base-uncased-emotion`using Hugging Face
- 6) **Gradio Interface** for a user-friendly web app experience

This AI assistant listens, understands, analyzes emotion, remembers past conversations, and responds naturally with human-like speech.

---

## 🛠 Requirements
Before running this project, ensure you have:
1. A **Hugging Face API Token** (to access LLaMA and Emotion models)
2. An **ElevenLabs API Key** (for TTS)

---

## Installation steps

1. **Clone the Repository**

git clone https://github.com/yourusername/Conversational_AI.git
cd Conversational_AI

2. **Create a Virtual Environment (optional)**

python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

3. **Install Dependencies**

pip install -r requirements.txt

4. **Setup API keys in app.ipynb**

5. **Usage**
notebook : app.ipynb
Follow the notebook cells to start the web app. This will launch a Gradio interface in your browser where you can:
1) Start the conversation only after entering a User ID eg. 1
2) Use microphone input or type your query
3) Hear voice responses


## Future Enhancements
Long-term vector memory storage
RAG model
Multilingual support
Android Application
Emotion-based response modulation
Human-like TTS

Hope you have an Interactive Conversation!
Feel free to open issues or pull requests. Contributions are welcome!

