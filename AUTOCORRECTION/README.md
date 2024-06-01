# AUTOCORRECTION
# Text Correction Python Script

This Python script is a simple text correction tool that corrects common spelling, grammar, and punctuation errors in a given input text. It utilizes various techniques such as edit distance calculation for spelling correction, predefined grammar correction rules, and substitution for common punctuation errors.

## Features

1. **Spelling Correction**: Uses an edit distance algorithm to suggest the correct spelling for misspelled words based on a dataset of known words.

2. **Grammar Correction**: Provides predefined rules to correct common grammar mistakes such as "could of" to "could've" and "your" to "you're".

3. **Punctuation Correction**: Corrects common punctuation errors such as excessive exclamation marks and incorrect spacing around punctuation marks.

## How to use

1. **Load Known Words**: The script loads a dataset of known words from text files provided as input.
   
2. **Input Text**: Enter the text you want to correct when prompted.
   
3. **Output**: The corrected text will be displayed, showing the corrections made for spelling, grammar, and punctuation errors.


## Usage

1. **Clone Repository**: Clone this repository to your local machine.

2. **Install Dependencies**: Ensure you have Python installed on your system. This script has no external dependencies beyond the Python standard library.

3. **Run the Script**: Execute the `main.py` script using Python. It will prompt you to enter the text you want to correct.

    ```bash
    python main.py
    ```

4. **View Corrected Text**: The script will output the corrected text to the console.

## Files

- `main.py`: The main Python script that performs text correction.
- `README.md`: This file, providing instructions and information about the script.
- `spelldataset7.txt`: Text file containing a dataset of known words for spelling correction.
- `american-words.10`, `american-words.20`, `american-words.35`: Text files containing additional datasets of known words.

## Dependencies

1. Python 3.x

2. **re module**: For regular expression operations.

3. **collections.Counter**: For creating a counter of words in the text.

## Contributions

Contributions to improve the script are welcome! If you have suggestions for new features, bug fixes, or optimizations, please feel free to open an issue or submit a pull request.
