# ECG Signal Analyzer

An AI-powered ECG signal analyzer using Gradio and Google Gemini AI that provides instant analysis, recommendations, and first aid suggestions.

## Features

- Upload ECG images for instant analysis
- AI-powered assessment (Normal/Abnormal detection)
- Detailed analysis with medical reasoning
- Immediate recommendations and first aid guidance
- User-friendly Gradio interface

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Ashwingaja/ECG_Analyzer.git
cd ECG_Analyzer
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Running Locally

Run the application:
```bash
python ecg_app.py
```

The app will be available at `http://localhost:7860`

## Requirements

- Python 3.8+
- Google Gemini API key

## Configuration

Update the API key in `ecg_app.py`:
```python
api_key = "YOUR_API_KEY_HERE"
```

Get your API key from [Google AI Studio](https://makersuite.google.com/app/apikey)

## Disclaimer

This tool provides AI-generated analysis for educational purposes only and should not replace professional medical diagnosis, advice, or treatment.

## License

MIT License
