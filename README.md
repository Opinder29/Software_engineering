EmotiBot Connect 🎙💬
Emotion-Aware Chatbot with Voice & Text Support

EmotiBot Connect is a transformer-based conversational AI that detects emotions from text or voice, provides personalized suggestions, and adapts based on user feedback.

🚀 Features
Voice 🎤 & text 💬 input (Gradio interface)
Transformer-based emotion detection (PyTorch)
Sentiment adjustment (TextBlob)
Dynamic suggestion generation from CSV
Feedback loop for better recommendations
Co-occurrence matrix visualization
📦 Installation
!pip install textblob gradio SpeechRecognition xgboost seaborn
!python -m textblob.download_corpora
🖥 Usage
iface.launch(debug=True)
Speak or type your message
Type "fun fact" for Hugging Face API facts
Type "bye" or "exit" to close the chat
📜 Workflow
Preprocessing – Tokenization, cleaning, padding
Transformer Model – Positional encoding, attention layers
Prediction Adjustments – Sentiment polarity overrides
Suggestions – Non-repeating advice from CSV
History – Saves past conversations to JSON
💾 Outputs
emotion_transformer_model.pth – Trained model
conversation_history.json – Chat log
About
No description, website, or topics provided.
Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 0 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Languages
Jupyter Notebook
97.7%
 
Python
2.3%
Footer
