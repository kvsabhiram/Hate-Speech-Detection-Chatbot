# Hate Speech Detection Chatbot

A lightweight chatbot that detects hate speech and offensive content using a BERT-based model (`unitary/toxic-bert`) with an interactive Gradio UI.

Features

- Classifies text as:
  -  Normal
  -  Offensive
  -  Hate Speech
- Uses LIME for model explanation
- Clean Gradio web interface
- Powered by HuggingFace Transformers

 Tech Stack

- Python 
- Transformers (`unitary/toxic-bert`)
- Gradio
- LIME (Local Interpretable Model-agnostic Explanations)
- NLTK

Installation

```bash
git clone https://github.com/yourusername/hate-speech-detection-chatbot.git
cd hate-speech-detection-chatbot
pip install -r requirements.txt
```

Run the App

```bash
python app/hate_speech_chatbot_gradio.py
```

The Gradio interface will launch in your browser.


License

MIT License

Model Reference

- [unitary/toxic-bert](https://huggingface.co/unitary/toxic-bert)

 Author

- [K.V.S.Abhiram](https://github.com/kvsabhiram)
- [Ashwin.k](https://github.com/ASHWIN-004)
