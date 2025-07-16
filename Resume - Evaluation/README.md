# LangGraph Resume Evaluation System

This project demonstrates a LangGraph-based system for evaluating resumes and generating appropriate responses using Google's Generative AI.

## Setup Instructions

### 1. Environment Setup

1. Clone this repository
2. Create a `.env` file in the project root directory
3. Add your Google API key to the `.env` file:
   ```
   GOOGLE_API_KEY=your_google_api_key_here
   ```

### 2. Get Google API Key

1. Go to [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Create a new API key
3. Copy the API key and add it to your `.env` file

### 3. Install Dependencies

Run the first cell in the notebook to install required packages:
```python
%pip install -q langgraph langchain langchain_google_genai python-dotenv
```

### 4. Run the Notebook

Execute all cells in order. The system will:
1. Load your resume data
2. Check qualifications against job requirements
3. Generate appropriate response messages

## Files

- `Langraph.ipynb` - Main notebook with the LangGraph workflow
- `.env` - Environment variables (not tracked in git)
- `.env.example` - Template for environment variables
- `.gitignore` - Ensures sensitive files are not committed
- `README.md` - This file

## Security

- Your API key is stored in `.env` file which is excluded from version control
- Never commit your actual API key to the repository
- Use the `.env.example` file as a template for other users

## Features

- Resume loading and parsing
- AI-powered qualification assessment
- Conditional workflow routing
- Automated response generation
- Environment variable management for security
