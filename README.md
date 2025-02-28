# LLM Dataset Creation and Preparation

## Description

This project demonstrates the process of creating and preparing a dataset for Large Language Model (LLM) training. It involves extracting text data from various sources, cleaning and preprocessing the data, and then structuring it into suitable formats like JSON and CSV. The dataset is then stored in different locations, including Hugging Face and Google Drive, and basic evaluation and versioning techniques are applied.


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data Sources](#data-sources)
- [Data Preprocessing](#data-preprocessing)
- [Dataset Structure](#dataset-structure)
- [Data Storage](#data-storage)
- [Dataset Evaluation](#dataset-evaluation)
- [Dataset Versioning](#dataset-versioning)
- [Contributing](#contributing)
- [License](#license)



## Installation

1. **Install Required Libraries:**

## Usage

1. **Data Collection:** Extract text from scanned documents (OCR), PDFs, DOCX files, and websites.
2. **Data Preprocessing:** Clean and preprocess the extracted text data.
3. **Dataset Structuring:** Convert the data to JSON and CSV formats.
4. **Data Storage:** Store the dataset on Hugging Face and Google Drive.
5. **Dataset Evaluation:** Perform basic evaluation checks on the dataset.
6. **Dataset Versioning:** Use DVC for dataset versioning.



## Data Sources

- Scanned documents (images)
- PDF documents
- DOCX (MS Word) documents
- Web scraping using Firecrawl



## Data Preprocessing

- Cleaning the text using regular expressions.
- Sentence splitting and tokenization using `tiktoken`.



## Dataset Structure

- **JSON Format:** Stores the text and source of each data point.
- **CSV Format:** Stores the data in a tabular format.



## Data Storage

- **Hugging Face:** The dataset is uploaded to Hugging Face Hub.
- **Google Drive:** The dataset is saved to Google Drive.



## Dataset Evaluation

- **Basic Statistics:** Word counts and frequency analysis.
- **Data Bias Detection:** Using word clouds for visualization.



## Dataset Versioning

- **DVC (Data Version Control):** Used to track and manage changes to the dataset.


## Contributing

Contributions are welcome! Please follow the standard GitHub workflow for submitting pull requests.


## License
MIT LICENSE
