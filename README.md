# A Temporal Analysis of Song Lyrics and Social Concerns in the U.S.

## Project Description
This project aims to explore the relationship between the content of lyrics from the Billboard Top 100 list and the most common searches on Google Trends by U.S. citizens from 2004 to 2024. The primary purpose is to identify whether there is a connection between the two or any notable patterns over time.

## Project Structure
```
Text_mining_final_project/
|-- documents/                  # Documents for the project
|   |-- Gentzkow (2010).pdf
|   |-- Hassan (2019).pdf
|   |-- hw02.pdf
|-- packages/                   # Package initialization file
|   |-- __pycache__.py          
|   |-- categories.py           # Create new categories
|   |-- preprocessing.py        # Data processing
|-- HW2_TEXT_MINING.pdf         # PDF with all our results and analysis
|-- hw02.ipynb                  # Principal Notebook
|-- README.md                   # Description the project structure
|-- requirements.txt            # Dependencies required to run
|-- setup.py                    # Installation and setup script
```

## Installation and Setup
### Requirements
To install the required dependencies, run:
```sh
pip install -r requirements.txt
```
### Running the Pipeline
1. **Prepare the Corpus:**
   - Choose a dataset from class materials or other sources like Kaggle, Google Books, or scraped web content.
   - Ensure the dataset covers diverse topics and contains metadata.
   
2. **Preprocess the Text:**
   - Run the preprocessing script to clean and normalize the text:
   ```sh
   python packages/preprocessing.py
   ```
   - This step includes removing stopwords, lemmatization, tokenization, and metadata extraction.

3. **Generate Dictionaries:**
   - Define dictionary categories in `categories.py`.
   - Run the script to generate dictionaries:
   ```sh
   python packages/categories.py
   ```
   - The script uses TF-IDF and other statistical methods to extract meaningful vocabulary.

4. **Analyze the Data:**
   - Open the Jupyter Notebook and execute the analysis:
    ```sh
   jupyter notebook hw02.ipynb
   ``` 
   - This notebook visualizes dictionary distributions and metadata-based insights.

## Methodology
1. **Data Collection**
   - blabla
2. **Dictionary Generation**
   - blabla
3. **Analysis**
   - blabla
   - 
## Contributions
This project is an academic exercise in text mining and dictionary-based analysis. Ethical considerations apply when scraping and analyzing text data.

## References
- Juan
- Trump
- Adam
