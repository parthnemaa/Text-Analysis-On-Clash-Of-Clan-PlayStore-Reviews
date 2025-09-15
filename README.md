# Text-Analysis-On-Clash-Of-Clan-PlayStore-Reviews

Text & Sentiment Analysis on Clash of Clans Play Store Reviews – This project uses NLP to clean, analyze, and classify user reviews from Google Play. It includes preprocessing, word frequency insights, visualizations, and sentiment classification to uncover player opinions, satisfaction trends, and feedback themes.

This repository provides a sentiment analysis workflow using game-based app review data. It processes user reviews, performs text cleaning and tokenization, and sets the foundation for building machine learning models to classify user sentiment.

## Features

- **Data preprocessing**: Lowercasing, punctuation removal, tokenization, and stopword filtering.
- **Sentiment label extraction**: Initial thumbs-up/down annotation for reviews.
- **Cleaned dataset**: Several columns support various feature engineering steps required for model training.

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook
- Standard Python libraries: pandas, numpy, re
- (Optional) Machine learning libraries: scikit-learn, TensorFlow/PyTorch

### Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/sentiment-analysis-gba.git
   ```
2. Install dependencies:

   ```bash
   pip install pandas numpy
   ```
3. Open the Jupyter notebook:

   ```bash
   jupyter notebook SENTIMENT-ANALYSIS-GBA.ipynb
   ```
4. Run each cell to process the dataset and follow the workflow described.

## Data Columns

| Column                | Description                                   |
|-----------------------|-----------------------------------------------|
| text                  | Original user review                          |
| thumbsUp              | Binary annotation (0/1)                       |
| lowercase_text        | Review with all lowercase letters             |
| no_special_chars      | Text with special characters and punctuation removed |
| tokenized_text        | Tokenized version of review text              |
| text_cleaned          | Cleaned and filtered tokens                   |
| text_cleaned_joined   | Cleaned tokens joined as text                 |

## Contributing

Feel free to fork, raise issues, and submit pull requests for improvements or bug fixes.
