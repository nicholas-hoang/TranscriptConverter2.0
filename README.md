![image](https://github.com/user-attachments/assets/d67a7c57-3355-4d95-adbf-51afbc4ea12a)

# TranscriptConverter2.0

A simple Streamlit application to convert VTT (Web Video Text Tracks) files into formatted Word documents. This tool allows users to upload multiple VTT files, process them, and download the resulting Word documents with organized transcriptions.




## Features

- Upload multiple VTT files at once.
- Automatic mapping of speakers to numerical labels.
- Removal of line breaks for cleaner text.
- Concatenation of text with timestamps and speaker information.
- Download formatted Word documents.

## Requirements

To run this application, you'll need the following dependencies:

- Python 3.8 or higher
- Streamlit
- pandas
- python-docx
- webvtt-py


## Requirements

Clone the repository:

```bash
git clone https://github.com/nicholas-hoang/TranscriptConverter2.0.git
```
You can install the required libraries using pip:

```bash
pip install streamlit pandas python-docx webvtt-py
```
Run the application:
```bash
streamlit run main.py
```
## Contributors
Nick Hoang

## License

This project is licensed under the MIT License.
