🎙️ Text-to-Speech System
A Deep Learning Based Speech Synthesis Project 


📌 Overview
This project implements a deep learning-based Text-to-Speech (TTS) system that converts written English text into human-like speech.

In many accessibility-focused or speech-based applications (like screen readers, voice assistants, audiobooks, etc.), natural-sounding and expressive speech is crucial. Traditional TTS systems often sound robotic or require massive datasets and complex pipelines.

This project uses the Tacotron 2 architecture — a state-of-the-art neural network model — combined with the Griffin-Lim vocoder to generate intelligible and fairly natural speech without needing complex vocoder models like WaveGlow.

✨ Features
Text-to-Speech Conversion: Converts plain English text into speech using a deep learning pipeline.
Tacotron 2 Architecture: Implements a sequence-to-sequence model with attention for generating mel-spectrograms from text.
Griffin-Lim Vocoder: Converts generated mel-spectrograms into audio waveforms using the Griffin-Lim algorithm.
Trained on LJSpeech Dataset: Fine-tuned on the publicly available LJSpeech dataset.
Easily input custom text via a script and generate corresponding .wav audio files.
Spectrogram & Attention Plots: Visualizes alignment and spectrograms for debugging and model understanding.

## 🎥 Demo Preview

![TTS Demo](./assets/demo.gif)


🔗Links
## 🔗 Links & Media

**📁 GitHub Repository:**  
[Text-to-Speech GitHub Repo](https://github.com/dikshat25/TextToSpeech)
**📹 Demo Video:**  
[Watch Full Demo](https://drive.google.com/drive/folders/1McUQXxP120t8BJnxS44jETvi8mOjdFV7?usp=sharing)
**🖼️ Screenshot Preview:**  
[View All Screenshots](https://drive.google.com/drive/folders/1y28jZ52TOIYmaxa05FmxBWcbdiKuv-Fv?usp=sharing)


🤖 Tech Stack
Language: Python
Deep Learning: PyTorch
Model: Tacotron 2
Vocoder: Griffin-Lim
Libraries: NumPy, Librosa, Matplotlib
Dataset: LJSpeech (13,100 English audio-text pairs)


🚀 Future Scope
Replace Griffin-Lim with WaveGlow or HiFi-GAN for more natural audio
Add multilingual support for Hindi, Marathi, etc.
Explore speaker conditioning for multi-voice synthesis
Create a frontend interface using Streamlit for user interaction
