# Moodflix: Movie Recommendation System with Sentiment Analysis

## Overview
Moodflix is an intelligent movie recommendation system that combines natural language processing, sentiment analysis, and voice interaction to provide personalized movie suggestions. The system features MovieBuddyAI, a voice-based assistant that understands user preferences through voice input and recommends movies based on mood, genres, actors, directors, and themes.

## Features
- 🎙️ MovieBuddyAI Voice Assistant
  - Natural voice interaction
  - Turn-based conversation system
  - Clear visual and audio indicators
  - Intelligent response generation
- 🎬 Smart Movie Recommendations based on:
  - User's current mood
  - Preferred genres
  - Favorite actors and directors
  - Time periods
  - Themes and plot elements
- 🤖 Natural Language Understanding
  - Complex query processing
  - Sentiment analysis
  - Context-aware responses
- 🎯 Personalized Scoring System
  - Mood-based weighting
  - Genre matching
  - Actor/director preferences
  - Era-based filtering
- 🔄 Interactive Follow-up
  - Refined recommendations
  - Detailed movie information
  - Alternative suggestions
- 🌐 Web Interface
  - User-friendly design
  - Real-time interaction
  - Alternative input methods

## Technical Stack
- Python 3.x
- Speech Recognition (Google Speech-to-Text)
- Text-to-Speech (gTTS, pyttsx3)
- Natural Language Processing
- Pandas for data handling
- Flask for web interface
- Deepgram API for enhanced speech recognition

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Moodflix.git
cd Moodflix
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Set up your environment variables:
```bash
cp .env.example .env
# Edit .env with your API keys and configurations
```

## Usage

### MovieBuddyAI Voice Assistant
1. Start the voice interface:
```bash
python main.py
```

2. Follow the voice prompts:
   - Press Enter when you see "YOUR TURN"
   - Speak your movie preferences
   - Wait for MovieBuddyAI's response
   - Ask follow-up questions or start a new recommendation

### Web Interface
1. Start the web server:
```bash
python app.py
```

2. Open your browser and navigate to:
```
http://localhost:5000
```

## Example Queries for MovieBuddyAI
- "I'm feeling sad today, what should I watch?"
- "Can you recommend a good action movie from the 90s?"
- "I want to watch something with Tom Hanks"
- "What's a good movie for a date night?"
- "Show me some sci-fi movies directed by Christopher Nolan"

## Project Structure
```
Moodflix/
├── main.py                 # Main application entry point
├── voice_movie_recommender.py  # MovieBuddyAI core logic
├── templates/             # Web interface templates
│   ├── home.html
│   └── results.html
├── static/               # Static files for web interface
├── data/                 # Movie database and related data
├── requirements.txt      # Project dependencies
└── README.md            # Project documentation
```

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Movie database provided by [source]
- Speech recognition powered by Google Speech-to-Text
- Text-to-speech capabilities from gTTS and pyttsx3
- Deepgram API for enhanced speech recognition

## Contact
For questions or feedback, please open an issue in the GitHub repository.
