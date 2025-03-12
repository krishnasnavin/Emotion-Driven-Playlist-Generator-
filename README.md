# Emotion-Driven Playlist Generator 🎵😊

Welcome to the **Emotion-Driven Playlist Generator**! This project uses **facial emotion detection** or **text-based sentiment analysis** to create personalized Spotify playlists based on your current mood. Whether you're happy, sad, angry, or calm, this app will curate a playlist that matches your emotions.

---

## **Features**
- **Facial Emotion Detection**: Uses a pre-trained deep learning model to detect your emotion from your webcam feed.
- **Text-Based Emotion Input**: Allows you to manually describe your mood, and the app will analyze it using sentiment analysis.
- **Spotify Integration**: Fetches songs from Spotify and creates a playlist tailored to your emotion.
- **User-Friendly GUI**: Built with `tkinter` for a seamless and intuitive user experience.

---

## **How It Works**
1. **Emotion Detection**:
   - The app detects your emotion using either:
     - **Facial Expression Analysis**: Captures your face via webcam and predicts your emotion using a pre-trained deep learning model.
     - **Text Input**: Analyzes your mood description using sentiment analysis (e.g., "I feel happy today").
2. **Playlist Generation**:
   - Based on the detected emotion, the app fetches songs from Spotify using the Spotify API.
   - Songs are selected based on audio features like **valence** and **energy**, which correlate with emotions.
3. **Playlist Creation**:
   - The app creates a new playlist in your Spotify account and adds the selected songs to it.
   - You receive a link to the playlist, ready to play!

---

## **Technologies Used**
- **Python**: The core programming language.
- **OpenCV**: For facial detection and webcam feed processing.
- **Keras/TensorFlow**: For loading and using the pre-trained emotion detection model.
- **Spotipy**: A Python library for interacting with the Spotify API.
- **TextBlob**: For sentiment analysis of text input.
- **Tkinter**: For building the graphical user interface (GUI).

---
