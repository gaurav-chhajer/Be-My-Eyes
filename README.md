# AI Vision Assistant 👁️‍🗨️

An intelligent web application that uses your device's camera and the Google Gemini API to describe scenes, read text, identify objects, and answer questions in real-time. It's designed to be a helpful "third eye" and includes voice commands for hands-free operation.

!

## ✨ Features

- **Live Camera Feed**: Uses the device's rear-facing camera.
- **AI-Powered Analysis**:
  - **Describe Scene**: Provides a detailed description of what the camera sees, focusing on key elements and layout.
  - **Read Text**: Performs Optical Character Recognition (OCR) to read any text in the frame.
  - **Identify Objects**: Lists the primary objects visible to the camera.
  - **Ask a Question**: Allows users to ask specific questions about the camera feed (e.g., "What color is the car?").
- **🗣️ Voice Commands**: Activate a hands-free mode to control the app's core features using your voice.
- **🔊 Text-to-Speech**: All AI-generated responses are read aloud for accessibility.
- **Responsive Design**: Works on both desktop and mobile devices.

## 🛠️ Tech Stack

- **Frontend**: HTML5, Tailwind CSS, JavaScript
- **APIs**:
  - **Google Gemini API**: For all vision and reasoning capabilities.
  - **Web Speech API**: For both Speech-to-Text (Recognition) and Text-to-Speech (Synthesis).
  - **WebRTC (getUserMedia)**: For accessing the camera feed.

## 🚀 Getting Started

This is a client-side only application and does not require a backend or build step.

### Prerequisites

- A modern web browser that supports the Web Speech API (Google Chrome is recommended).
- A working camera and microphone.
- Your own Google Gemini API Key.

### Installation & Setup

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/gaurav-chhajer/Be-My-Eyes.git
    ```

2.  **Get a Gemini API Key:**
    - Go to [Google AI Studio](https://aistudio.google.com/app/apikey).
    - Click **"Create API key"** and copy the generated key.

3.  **Add the API Key to the code:**
    - Open the `index.html` file.
    - Find the following line in the `<script>` section:
      ```javascript
      const apiKey = ""; // IMPORTANT: Paste your own Google Gemini API key here
      ```
    - Paste your key between the quotes.

4.  **Run the application:**
    - Simply open the `BeMyEyes.html` file in your web browser. You may need to grant the page permission to access your camera and microphone.

## Usage

1.  Click **Start Camera**.
2.  Point your camera at the scene or object you want to analyze.
3.  Use the buttons or activate voice commands to interact with the assistant.
    - **To use voice commands:** Click "Activate Voice". First say "Start" to make the assistant listen for commands, then say "Describe", "Read", "Identify", or "Ask [your question]".

---
Made with by Gaurav Chhajer
