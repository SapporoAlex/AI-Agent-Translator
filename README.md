# AI Agent Japanese to English Excel Translator

This Python script automates the translation of Japanese text in an Excel file to English using an AI agent powered by LLaMA and DuckDuckGo for place name verification. The translated text is inserted into the adjacent column.

## Features
- Uses `phi.agent` with `Groq` to translate Japanese text into English.
- Utilizes `DuckDuckGo` for confirming place names.
- Reads an Excel file containing Japanese text.
- Writes the English translations into the column next to the original text.
- Saves the updated file with a new name.

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Required dependencies (listed below)

### Dependencies
Install the required libraries using pip:
```sh
pip install phi openpyxl python-dotenv
```
## Usage
1. Place your Excel file in the appropriate directory.
2. Update the file_name variable in the script to match your file name.
3. Run the script:
```sh
Translator_Agent.py
```
4. The script will process the file and save a translated version with the prefix "Translated".
## Configuration
- Modify the file_name variable to point to your desired Excel file.
- Ensure .env is properly set up if required for API keys.
## Notes
- The script assumes that Japanese text is in the first column (Column A) and English translations should be placed in the second column (Column B).
- It relies on phi.agent and Groq, so make sure you have the appropriate API access.
## License
MIT License

## Author
Alexander McKinley
