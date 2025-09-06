# Relevant Stock Recommender

A semantic search system that finds relevant companies based on natural language queries using vector similarity search. This project leverages financial data from Yahoo Finance, stores company descriptions in Pinecone vector database, and uses HuggingFace embeddings to find companies that match user queries about business characteristics, locations, or industries.

## Features

- Fetch comprehensive stock information from Yahoo Finance
- Generate text embeddings using HuggingFace Sentence Transformers
- Store and search company descriptions in Pinecone vector database
- Perform semantic similarity search to find relevant companies
- Process SEC company ticker data for comprehensive coverage
- Generate AI-powered explanations using Google Gemini
- Parallel processing for efficient data ingestion

## Prerequisites

- Python 3.10+
- GPU support (recommended)
- Google Colab (for notebook execution)
- Pinecone account and API key
- Google AI API key (for Gemini)

## Required Packages 

bash <br />
pip install yfinance langchain_pinecone python-dotenv langchain-community sentence_transformers

## Installation

1. Clone this repository:

git clone [https://github.com/yourusername/relevant-stock-recommender.git](https://github.com/anbguye/relevant-stock-recommender.git) <br />
cd relevant-stock-recommender

2. Install dependencies:

bash <br />
pip install -r requirements.txt

3. Set up environment variables:

Create a `.env` file with your API keys and configurations:<br />
PINECONE_API_KEY=your_pinecone_api_key <br />
GOOGLE_API_KEY=your_google_api_key <br />


## Usage

1. Open the `relevant-stock-recommender.ipynb` notebook in Google Colab or Jupyter
2. Follow the notebook cells to:
   - Install required dependencies
   - Fetch SEC company ticker data
   - Process stock information from Yahoo Finance
   - Generate embeddings for company descriptions
   - Store data in Pinecone vector database
   - Query for relevant companies using natural language
   - Generate AI explanations with Google Gemini

## Project Structure

relevant-stock-recommender/<br />
├── relevant-stock-recommender.ipynb # Main notebook<br />
├── README.md # Project documentation<br />
└── .env # Environment variables (not tracked)<br />


## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- YFinance for financial data
- LangChain for NLP processing
- Sentence Transformers for text embeddings
- Pinecone for vector similarity search
- Google Gemini for AI-powered explanations

## Contact

Anthony Nguyen - [@anbguye](https://twitter.com/anbguye) <br />
Project Link: https://github.com/anbguye/relevant-stock-recommender
