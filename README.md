 data-extraction
Here’s a README file for your GitHub project, combining the details from both of your files.

---

 Article Text Extraction and Analysis

 Overview
This project provides scripts to extract article text and analyze readability metrics from a list of URLs. It uses `requests` and `BeautifulSoup` for web scraping, and `textstat` for readability calculations. Data extracted and analyzed includes metrics like average sentence length, word count, fog index, and other readability factors. The analysis results are saved in an Excel file.

 Features
- **Text Extraction**: Extracts article title and content from given URLs.
- **Readability Analysis**: Calculates readability metrics like fog index, complex word percentage, and average sentence length.
- **Export to Excel**: Saves the analysis results in an Excel file.
- **URL List from Excel**: Reads URLs from an Excel file and extracts/saves article content in individual text files.

 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/username/repository-name.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd repository-name
   ```
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

 Usage

### 1. Extract and Analyze Articles
Run the script to extract text from a list of URLs, analyze readability metrics, and save the results in an Excel file:
```bash
python extract_and_analyze.py
```
This script reads URLs from the `Input.xlsx` file and processes each URL.

 2. Extract and Save Articles as Text Files
Run the script to save each article's title and content in individual text files named after the article’s ID:
```bash
python extract_text_to_files.py
```

 File Structure

- `extract_and_analyze.py`: Script to extract text and analyze readability metrics.
- `extract_text_to_files.py`: Script to extract article content and save it to a `.txt` file.
- `Input.xlsx`: Excel file containing URLs and IDs for processing.
- `output_<timestamp>.xlsx`: Output file generated after readability analysis, saved with a timestamp.

 Contributing
Contributions are welcome! If you would like to contribute to this project, please fork the repository and create a pull request.

License
This project is licensed under the MIT License.

--- 

This template gives an overview of the purpose, usage, and setup instructions, making it easy for other developers to understand and contribute to the project. Let me know if you need any additional customization!
