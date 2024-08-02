# Sentiment Unleashed: Amazon Reviews NLP Analysis 

Welcome to the exciting journey of unraveling sentiments hidden within Amazon reviews! This project leverages the power of natural language processing (NLP) to categorize sentiments as positive, negative, or neutral across various product categories.

## PROCESS

### 🚀 Data Processing 🔄

Utilize PySpark or Pandas to clean, transform, and prepare the Amazon reviews data. Explore the magic in:
- `processing/process_amazon_reviews_pandas.py`
- `processing/process_amazon_data_spark.py`

### 🚀 Analysis 

Dive into detailed analysis with Jupyter notebooks:
- Exploratory Data Analysis (EDA)
- Predictions: Star Ratings, Product Categories, Sentiment Labels
- Statistical Significance Testing

### 🚀 Natural Language Processing (NLP) 

Explore the NLP techniques used:
- Text Cleaning: Lowercasing, HTML unescaping, punctuation removal
- Sentiment Analysis: Vader Sentiment library

## GETTING STARTED

### 🚀 Recommended: Download Preprocessed Data and Models 📥

Before diving into the code (especially the notebooks), we strongly recommend downloading the preprocessed output dataset directory and models hosted on archive.org. This step will save you time by avoiding the need to rerun the entire data processing phase.

- **Output Datasets**: Available in `.csv.gz` format: [Download Output Datasets](https://archive.org/download/amazon_reviews_dump)
- **Models**: Available in `.joblib.gz` format: [Download Models](https://archive.org/download/amazon_reviews_dump)

The processing package, although insightful, is mainly included to showcase our data cleaning and preparation process.

### 🚀 Requirements 

Just make sure you have Python 3.11 installed, and we'll take care of the rest!

### 🚀 Setting Script Permissions 

Before proceeding with either the automatic setup or manual exploration, please ensure that the scripts have the necessary permissions to execute. This can be done by navigating to the root directory of the project and running the following commands:

```bash
chmod +x ./scripts/setup.sh
chmod +x ./scripts/download-data.sh
```


To run the script, navigate to the `analysis` directory and execute:

```bash
python3 run_models.py
```

This will generate classification reports and scores for the Bayes models, displaying them in the standard output. Make sure you have the required models and validation data available before running this script.

## 🚀 Spark Warning

Running Spark jobs requires significant memory and may not be suitable for machines with limited resources.
