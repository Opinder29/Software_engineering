# EmotiBot Connect 🎙💬  
**Emotion-Aware Chatbot with Voice & Text Support**

## 🚀 Features
- Voice 🎤 & Text 💬 input (Gradio interface)  
- Transformer-based emotion detection (PyTorch)  
- Sentiment adjustment (TextBlob)  
- Dynamic suggestion generation from CSV  
- Feedback loop for better recommendations  
- Co-occurrence matrix visualization  

## 📦 Installation

Run these commands to install dependencies:

```bash
pip install textblob gradio SpeechRecognition xgboost seaborn
python -m textblob.download_corpora
🖥 Usage
Start the interface with:
iface.launch(debug=True)
Then speak or type your message.
Type "fun fact" for Hugging Face API facts.
Type "bye" or "exit" to close the chat.

📜 Workflow
Preprocessing – Tokenization, cleaning, padding

Transformer Model – Positional encoding, attention layers

Prediction Adjustments – Sentiment polarity overrides

Suggestions – Non-repeating advice from CSV

History – Saves past conversations to JSON

💾 Outputs
emotion_transformer_model.pth – Trained model

conversation_history.json – Chat log
