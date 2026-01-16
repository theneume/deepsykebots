# Photography Academy AI Bot

A personalized AI-powered photography assistant built with Flask, using the Deepsyke natal type system.

## 🚀 Quick Start

This bot is deployed on [Render.com](https://render.com).

## 📋 Features

- **Natal Type Calculation**: Uses the correct 9-year cycle algorithm
- **Personalized Responses**: Type-specific engagement (SS, SD, DS, DD)
- **Direct Communication**: No repetitive openings/closings
- **Cultural Avatars**: Dynamic avatar references
- **Business Knowledge**: Photography Academy-specific content

## 🔧 Setup

### Requirements
- Python 3.11+
- Flask
- See `requirements.txt` for dependencies

### Installation
```bash
pip install -r requirements.txt
python app.py
```

The bot will run on port 9009.

## 📁 Project Structure

```
.
├── app.py                      # Main Flask application
├── requirements.txt            # Python dependencies
├── natal_calculator.py         # Type calculation logic
├── deepsyke_core_rag.json      # Core configuration
├── cultural_avatars_rag.json   # Cultural avatars database
├── engagement_protocol.json    # Type-specific engagement
├── business_rag.json           # Business knowledge
├── ai_system_prompt.txt        # AI system prompt
└── templates/
    └── index.html              # Frontend interface
```

## 🎯 Natal Types

The bot calculates natal types using a 9-year cycle algorithm:

- **SS (Steady Support)**: Depth-focused, contemplative
- **SD (Structured Development)**: Step-by-step, guided
- **DS (Dynamic Search)**: Creative, exploratory  
- **DD (Direct Drive)**: Results-oriented, efficient

Each type receives unique, personalized responses.

## 📝 Recent Updates

- ✅ Fixed natal calculator (9-year cycle algorithm)
- ✅ Removed repetitive "peaceful rhythm" phrases
- ✅ Updated SS intro to focus on "building"
- ✅ Implemented direct response structure
- ✅ Enhanced type-specific gravitors

## 🌐 Deployment

Deployed on Render.com with automatic deployment from GitHub.

## 📞 Support

For issues or questions, please refer to the project documentation.