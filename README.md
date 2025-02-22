# Educational Content Scraper & AI Comparison

## Overview
This repository contains code for scraping educational content from various sources, generating AI-created content on the same topics, and comparing the vocabulary used in both. The workflow consists of data collection, processing, AI-generated content creation, and vocabulary analysis.

## Repository Structure
```
📂 data/                # Folder containing raw and processed data
📂 gpt_data/            # AI-generated content storage
📂 notebooks/           # Jupyter notebooks for different stages of processing
│── 01_web_scrapping_textbook.ipynb     # Scrapes educational content
│── 02_process_data.ipynb               # Processes the scraped data
│── 03_visualize_master_data.ipynb      # Data visualization
│── 04_sintetic_data.ipynb              # Generates AI-created content
│── 05_process_gpt_output_data.ipynb    # Processes AI-generated content
│── 06_compare_vocabulary.ipynb         # Compares vocabulary between real and AI content
📂 venv/               # Virtual environment (if applicable)
📄 .env                # Environment variables file
📄 README.md           # Project documentation
📄 requirements.txt    # Dependencies for the project
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name
   ```
2. Set up a virtual environment (optional but recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. **Scrape educational content:** Run `01_web_scrapping_textbook.ipynb` to collect data.
2. **Process the data:** Use `02_process_data.ipynb` to clean and prepare scraped content.
3. **Visualize the data:** Run `03_visualize_master_data.ipynb` for exploratory analysis.
4. **Generate AI content:** Execute `04_sintetic_data.ipynb` to generate AI-written text.
5. **Process AI output:** Use `05_process_gpt_output_data.ipynb` to clean AI-generated text.
6. **Compare vocabulary:** Run `06_compare_vocabulary.ipynb` to analyze differences in word usage.


