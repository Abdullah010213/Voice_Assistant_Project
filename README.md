# LiveKit Voice AI Assistant

A real-time voice AI assistant built with LiveKit, Google's Gemini model, and noise cancellation for seamless interactions.

## Features

- 🎙️ Real-time voice interactions
- 🤖 Powered by Google's Gemini 2.0 Flash model
- 🔇 Built-in noise cancellation
- 🏷️ Customizable instructions and responses
- 🚀 Easy deployment with LiveKit

## Prerequisites

- Python 3.8+
- LiveKit server (self-hosted or cloud)
- Google Cloud API credentials (for Gemini)

## Installation

1. Clone the repository:
   git clone https://github.com/your-username/livekit-voice-assistant.git
   cd livekit-voice-assistant

2. Install dependencies:
   pip install -r requirements.txt

3. Create a .env file with your credentials:
   LIVEKIT_URL=wss://your-livekit-server.com
  LIVEKIT_API_KEY=your_api_key
  LIVEKIT_API_SECRET=your_api_secret
  GOOGLE_APPLICATION_CREDENTIALS=path/to/your/google-credentials.json

## Requirements
- livekit-agents
- livekit-agents[google]~=1.0
- livekit-plugins-noise-cancellation~=0.2
- python-dotenv




  
