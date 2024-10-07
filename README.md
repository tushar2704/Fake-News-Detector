# Fake-News-Detector

## Overview

This Streamlit application uses CrewAI and the Groq API to analyze news articles related to any topic for potential false or misleading information. The app employs three AI agents (a researcher, a fact-checker, and an analyst) to perform a comprehensive analysis of input news articles.

## Features

- User-friendly interface for inputting news articles
- AI-powered analysis using CrewAI agents
- Utilizes the Groq API for advanced language processing
- Provides detailed analysis results
- Responsive design with Streamlit

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.7+
- Groq API key
- Internet connection for web searches

## Installation

1. Clone the repository:
   ```
   git clone hhttps://github.com/tushar2704/Fake-News-Detector.git
   cd Fake-News-Detector
   ```

2. Create and activate a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use: venv\Scripts\activate
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

4. Set up your Groq API key:
   - Create a `.env` file in the project root
   - Add your Groq API key: `GROQ_API_KEY=your_api_key_here`

## Usage

1. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

2. Open your web browser and go to the URL provided by Streamlit (usually `http://localhost:8501`)

3. Enter a news article in the text area and click "Analyze News"

4. Wait for the AI agents to process the information and provide their analysis

## Project Structure

```
us-election-2024-false-news-predictor/
│
├── app.py                 # Main Streamlit application
├── requirements.txt       # Project dependencies
├── .env                   # Environment variables (not in version control)
├── README.md              # Project documentation
└── venv/                  # Virtual environment (not in version control)
```

## How It Works

1. **Research Analyst**: Finds relevant information about the news article
2. **Fact Checker**: Verifies the claims made in the news article
3. **Political Analyst**: Analyzes the article for potential bias or false information

The CrewAI framework orchestrates these agents to work together and provide a comprehensive analysis.

## Customization

You can customize the agents, tasks, or add new features by modifying the `app.py` file. Some ideas for expansion:

- Add more specialized agents (e.g., a historical context expert)
- Implement result caching for improved performance
- Add user authentication for secure access
- Integrate with external fact-checking APIs or databases

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

This application is for educational and demonstration purposes only. It should not be used as the sole source for determining the veracity of news articles. Always cross-reference information with reputable sources.

## Acknowledgments

- [CrewAI](https://github.com/joaomdmoura/crewAI)
- [Streamlit](https://streamlit.io/)
- [Groq](https://groq.com/)
- [LangChain](https://github.com/hwchase17/langchain)

## Contact

If you have any questions or feedback, please open an issue on this repository.
```

This README.md provides a comprehensive guide for users and potential contributors to understand, set up, and use your US Election 2024 False News Predictor application. It includes sections on installation, usage, project structure, customization, and more. You can further customize this README to fit any specific details or requirements of your project.