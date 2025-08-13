# EmotiBot Connect 🎙💬  
**Emotion-Aware Chatbot with Voice & Text Support**

EmotiBot Connect is a transformer-based conversational AI designed to detect emotions from both text and voice inputs. It provides personalized suggestions and continuously improves by adapting based on user feedback.

---

## 🚀 Features

- **Voice 🎤 & Text 💬 Input:** Interactive Gradio interface supporting speech and typing.  
- **Transformer-Based Emotion Detection:** Built with PyTorch for accurate emotion recognition.  
- **Sentiment Adjustment:** Uses TextBlob to fine-tune emotion predictions based on sentiment polarity.  
- **Dynamic Suggestions:** Offers personalized, non-repetitive advice generated from CSV data.  
- **Feedback Loop:** Improves recommendations over time through user feedback.  
- **Co-occurrence Matrix Visualization:** Visualize emotion patterns using Seaborn.

---

## 📦 Installation

To get started, install the required Python packages:

```bash
pip install textblob gradio SpeechRecognition xgboost seaborn
python -m textblob.download_corpora
🖥 Usage
Launch the chatbot interface:
iface.launch(debug=True)
Interact by speaking or typing your message.

Useful commands:

Type "fun fact" to receive interesting facts via the Hugging Face API.

Type "bye" or "exit" to close the chat.

## 📜 Workflow 
- Preprocessing – Tokenization, cleaning, padding
- Transformer Model – Positional encoding, attention layers
- Prediction Adjustments – Sentiment polarity overrides
- Suggestions – Non-repeating advice from CSV
- History – Saves past conversations to JSON

## 💾 Outputs
- `emotion_transformer_model.pth` – Trained model
- `conversation_history.json` – Chat log
# About

EmotiBot Connect aims to create a more empathetic AI chatbot experience by combining advanced NLP techniques with emotion awareness. It’s a project designed to blend technology and emotional intelligence for meaningful user interaction. 
