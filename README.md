# Automated Job Application System

A browser-based application that automatically applies to jobs using AI-powered user profiling and intelligent form filling.

## Features

- 🤖 **AI-Powered Job Matching**: Uses machine learning to match jobs to user preferences
- 🌐 **Multi-Platform Support**: Scrapes jobs from Indeed, LinkedIn, and other job boards
- 📝 **Automated Form Filling**: Intelligently detects and fills application forms
- 💌 **Dynamic Cover Letters**: Generates personalized cover letters for each application
- 📊 **Application Tracking**: Tracks all applications and their status
- 🔒 **Privacy-Focused**: All data stored locally, no external data sharing

## Installation

1. Clone or download this project
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Install ChromeDriver for Selenium automation
4. Configure your settings in `config/settings.json`

## Quick Start

1. **Run the demo** to see how it works:
   ```bash
   python demo.py
   ```

2. **Set up your profile** by editing `data/sample_user_profile.json`

3. **Run the main application**:
   ```bash
   python main.py --user-id your_id --query "python developer" --location "San Francisco"
   ```

## Configuration

Edit `config/settings.json` to customize:
- Browser settings (headless mode, profile path)
- Resume file path
- Application limits and delays
- Job source preferences
- AI matching thresholds

## Safety Features

- **Manual Review Mode**: Review applications before submission
- **Rate Limiting**: Prevents too many applications per day
- **Form Validation**: Ensures forms are properly filled
- **Error Handling**: Graceful handling of website changes

## Project Structure

```
job_application_system/
├── src/
│   ├── ai/                 # AI components
│   ├── browser/            # Browser automation
│   ├── data/               # Data management
│   └── utils/              # Utilities
├── data/                   # User data and database
├── config/                 # Configuration files
├── logs/                   # Application logs
└── tests/                  # Test files
```

## Legal and Ethical Considerations

- **Terms of Service**: Ensure compliance with job site terms of service
- **Rate Limiting**: Respect website rate limits and robots.txt
- **Accuracy**: Always review applications before submission
- **Privacy**: Keep personal data secure and local

## Disclaimer

This tool is for educational and personal use only. Users are responsible for:
- Complying with website terms of service
- Ensuring application accuracy
- Following employment laws and regulations
- Respecting rate limits and website policies

## Support

For issues or questions, please check the documentation or create an issue in the project repository.
