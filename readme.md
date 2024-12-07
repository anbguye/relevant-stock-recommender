# Relevant Stock Recommender

A machine learning-powered system that recommends relevant stocks based on news articles and market data. This project uses natural language processing and financial data analysis to identify potential investment opportunities.

## Features

- Process news articles and market data in real-time
- Identify relevant stocks based on news content
- Analyze market trends and correlations
- Generate stock recommendations using advanced NLP techniques
- Integrate with financial data providers (Yahoo Finance)

## Prerequisites

- Python 3.10+
- GPU support (recommended)
- Google Colab (for notebook execution)

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
PINECONE_ENVIRONMENT=your_pinecone_environment <br />


## Usage

1. Open the `relevant-stock-recommender.ipynb` notebook in Google Colab or Jupyter
2. Follow the notebook cells to:
   - Process financial news articles
   - Generate stock recommendations
   - Analyze market correlations
   - View recommended stocks

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

## Contact

Anthony Nguyen - [@anbguye](https://twitter.com/anbguye) <br />
Project Link: https://github.com/anbguye/relevant-stock-recommender
