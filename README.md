# Multi-Agent Architecture for Market Research & Use Case Generation

This project showcases a multi-agent architecture for market research and use case generation using AI and machine learning technologies. The system is designed with three main agents:

1. **Browser Agent**: Researches company information and classifies the industry.
2. **Market Standards & Use Case Generation Agent**: Analyzes industry trends and proposes AI/ML use cases.
3. **Resource Asset Collection Agent**: Collects Kaggle datasets related to the industry.

The project uses `Streamlit` for a user-friendly interface, `BeautifulSoup` for web scraping, `Qdrant` for vector-based storage, and `SentenceTransformers` for embedding generation.

## Requirements

To run this project, ensure you have Python 3.7+ installed and the following dependencies:

- `streamlit`: For the web interface.
- `requests`: To make HTTP requests to fetch company data.
- `beautifulsoup4`: To parse and extract relevant data from HTML pages.
- `qdrant-client`: For interacting with the Qdrant vector database.
- `sentence-transformers`: For generating sentence embeddings.
- `kaggle`: To fetch datasets from Kaggle.

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/multi-agent-market-research.git
   cd multi-agent-market-research
