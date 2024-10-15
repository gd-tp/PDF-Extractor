# PDF Extractor

PDF Extractor is a versatile Python application with a graphical user interface that provides two main functionalities:

1. PDF Table Extractor: Extract tables from PDF files
2. PDF URL Extractor: Extract hyperlinks from PDF files

## Features

### PDF Table Extractor

- Extract tables from multiple PDF files in a directory
- Option to combine tables or keep them separate
- Multiple extraction strategies to handle different table structures
- Test run option to try all strategies on the first PDF
- Progress tracking for extraction process

#### Extraction Strategies:

- Default
- Lines
- Lines-2
- Text
- Text-2

### PDF URL Extractor

- Extract hyperlinks from multiple PDF files in a directory
- Saves extracted URLs to CSV files
- Progress tracking for extraction process

## How to Use

1. Launch the application
2. Choose the desired tab: "Table Extractor" or "URL Extractor"

### Table Extractor

1. Select the input directory containing PDF files
2. (Optional) Choose a different output directory
3. Select whether to combine tables or keep them separate
4. Choose an extraction strategy
5. (Optional) Check "Test Run" to try all strategies on the first PDF
6. Click "Extract Tables" to begin the process

### URL Extractor

1. Select the input directory containing PDF files
2. Click "Extract URLs" to begin the process

## Output

- Table Extractor: CSV files containing extracted tables
- URL Extractor: CSV files containing extracted hyperlinks with page numbers

## Notes

- The application provides real-time progress updates during extraction
- Extracted files are saved in the input directory by default, unless a different output directory is specified for table extraction
- For URL extraction, files are always saved in the input directory

This application simplifies the process of extracting structured data and hyperlinks from PDF files, making it useful for data analysis, web scraping, and document processing tasks.