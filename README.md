
# Survey Sentiment Analysis

This repository contains a Jupyter Notebook that performs sentiment analysis on survey responses. The responses are clustered, and sentiment analysis is applied to each cluster to provide insights into the sentiments and topics of the survey responses.

## Features

- Text preprocessing
- TF-IDF Vectorization
- Dimensionality Reduction using Truncated SVD
- Clustering using KMeans
- Sentiment Analysis with a pre-trained model
- Topic Modeling using LDA

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/survey_sentiment_analysis.git
```

2. Navigate to the project directory:

```bash
cd survey_sentiment_analysis
```

3. Create a virtual environment and activate it:

```bash
python3 -m venv venv
source venv/bin/activate
```

4. Install the required packages:

```bash
pip install -r requirements.txt
```

## Usage

1. Make sure you have the survey responses in a CSV file named \`survey_responses.csv\`.
2. Run the Jupyter Notebook:

```bash
jupyter notebook survey_sentiment_analysis.ipynb
```

3. Follow the steps in the notebook to preprocess the data, apply clustering, perform sentiment analysis, and extract topics.

## Requirements

- pandas
- numpy
- matplotlib
- scikit-learn
- transformers

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
