# PDFDecryptor

PDFDecryptor is a tool designed to help you unlock password-protected PDF files using a wordlist attack. This tool tries each password from the provided wordlist until it finds the correct one or exhausts all possibilities.

## Features

- Supports both Windows and Linux platforms.
- Uses a wordlist to crack the password of PDF files.
- Provides a progress bar to show the cracking progress.

## Requirements

- Python 3.x
- `pikepdf` library
- `tqdm` library
- `termcolor` library
- `pyfiglet` library

## Installation

To install the required libraries, you can run the script, and it will automatically install missing dependencies. Alternatively, you can manually install them using pip:

```sh
pip install pikepdf tqdm termcolor pyfiglet
```
# Usage
1. Clone or download this repository.
1. Ensure you have Python 3.x installed on your system.
1. Run the pdfdecryptor.py script:
```sh
python pdfdecryptor.py <path_to_pdf> <path_to_wordlist>
```
Replace <path_to_pdf> with the path to your password-protected PDF file and <path_to_wordlist> with the path to your wordlist file.
# Example
```sh
python pdfdecryptor.py protected.pdf wordlist.txt
```
# Notes
- Make sure your wordlist is comprehensive enough to include the possible password for the PDF.
- The time taken to crack the password depends on the length and complexity of the wordlist.
# Disclaimer
This tool is intended for educational purposes only. Do not use it for illegal activities. Always ensure you have the legal right to access the PDF files you are attempting to unlock.


