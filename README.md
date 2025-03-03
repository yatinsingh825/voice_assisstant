# Swift Voice Assistant

Swift is a powerful, feature-rich voice assistant built in Python that responds to voice commands and performs a wide variety of tasks, from answering questions to generating code using AI.

## Features

Swift comes packed with numerous capabilities:

### Basic Interactions
- Responds to greetings and casual conversations
- Tells time and date
- Provides information about itself and its creator

### Web & Information
- Searches the web with Google
- Looks up information on Wikipedia
- Provides weather forecasts for any location
- Fetches latest news headlines
- Translates text between languages
- Provides dictionary definitions

### System Operations
- Opens applications and websites
- Performs internet speed tests
- Displays IP address information
- Pings websites and checks connectivity
- Adjusts screen brightness
- Searches for files on your computer

### Productivity Tools
- Shows calendar
- Sets reminders and manages to-do lists
- Provides motivational quotes
- Tells jokes for a quick break

### Advanced Tools
- Generates secure passwords of specified length and complexity
- Analyzes password strength with improvement suggestions
- Converts between different currencies with current exchange rates
- Generates code using Google's Gemini AI based on natural language descriptions

## Setup

### Prerequisites
- Python 3.7+
- Required libraries (see requirements.txt)
- API keys for:
  - Google Gemini (Code Generation)
  - OpenWeatherMap (Weather Forecasts)
  - NewsAPI (News Headlines)

### Installation

1. Clone this repository:
```
git clone https://github.com/yourusername/swift-voice-assistant.git
cd swift-voice-assistant
```

2. Install required packages:
```
pip install -r requirements.txt
```

3. Update API keys in the code:
```python
# In the VoiceAssistant class __init__ method:
self.news_api_key = "YOUR_NEWS_API_KEY"
self.weather_api_key = "YOUR_WEATHER_API_KEY"
self.gemini_api_key = "YOUR_GEMINI_API_KEY"
```

## Usage

Run the assistant:
```
python swift_assistant.py
```

Activate the assistant by saying "Swift" followed by your command.

### Sample Commands

- "Swift, what time is it?"
- "Swift, what's the weather in New York?"
- "Swift, search for machine learning tutorials"
- "Swift, open Chrome"
- "Swift, remind me to attend the meeting at 3 PM"
- "Swift, generate a secure password with 16 characters"
- "Swift, convert 100 dollars to euros"
- "Swift, generate code for a web scraper that extracts headlines"

## Command List

### Information
- "hello" - Greet the assistant
- "time" - Get current time
- "date" - Get current date
- "who is [person]" - Get Wikipedia info about a person
- "what is [thing]" - Get information about a concept

### Web & Search
- "search [query]" / "google [query]" - Search the web
- "open website [URL]" / "visit [URL]" - Open a website
- "what is my ip" - Get your IP address information
- "check internet speed" - Run an internet speed test
- "ping [website]" - Ping a website

### System
- "open [application]" - Open an application
- "search files [query]" / "find files [query]" - Search for files
- "brightness [level]" / "screen [level]" - Adjust screen brightness

### Utilities
- "weather [location]" / "forecast [location]" - Get weather information
- "news" / "headlines" - Get the latest news
- "translate [text]" - Translate text
- "define [word]" / "meaning of [word]" - Look up word definitions
- "show calendar" / "calendar" - Display calendar
- "tell me a joke" / "joke" - Hear a joke
- "motivate me" / "quote" - Get a motivational quote

### Productivity
- "reminder [task] at [time]" / "remind me to [task]" - Set a reminder
- "todo [task]" / "task [description]" - Add a to-do item
- "list" - Show all reminders and to-dos

### Security & Finance
- "generate password" - Create a secure password
- "check password" - Analyze password strength
- "convert currency" / "exchange rate" - Currency conversion

### AI-Powered
- "generate code [description]" / "code for [functionality]" - Generate code using AI
- "implement [programming task]" - AI-powered code generation

### Help & Exit
- "what can you do" / "help" / "capabilities" - Show all capabilities
- "exit" / "goodbye" / "stop" - Exit the assistant

## Customization

You can customize Swift by:
- Adding new commands in the `commands` dictionary
- Creating new methods for specific functionality
- Modifying voice properties for speed and tone
- Adjusting wake word sensitivity



## Acknowledgments

- Thanks to all the open-source libraries that made this project possible
- Special thanks to Google's Gemini API for code generation capabilities
