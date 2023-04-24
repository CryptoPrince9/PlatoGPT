# PlatoGPT
PlatoGPT is a Python app that can extract text from a variety of file types, including PDFs, Word documents, PowerPoint presentations, Excel spreadsheets, and EPUB files. It can also generate summaries of the extracted text using the autogpt library. The app has a simple GUI built using the tkinter library, with buttons to initiate text extraction and summarization, and to display a message box when the processing is complete.

Features:

Extract text from PDFs, Word documents, PowerPoint presentations, Excel spreadsheets, and EPUB files.
Generate summaries of the extracted text using the autogpt library.
Simple GUI with buttons to initiate text extraction and summarization, and to display a message box when processing is complete.
How to use PlatoGPT:

Place the files you want to extract text and summarize in the data directory.
Run the app by typing: python app.py in the terminal
Click the "Extract Text" button to extract text from all files in the data directory.
Click the "Summarize Text" button to generate summaries of the extracted text using the autogpt library.
The results will be saved as separate text files with the same name as the original files, but with "_summary" added to the end.
Click the "OK" button to close the app and view the results.
PlatoGPT can be used to help train auto-gpt models by providing a large dataset of extracted text and summaries for use in training. The app automates the process of extracting text and generating summaries, saving time and effort for researchers and developers.
Installation
Download and install Python on your computer if you don't have it already. You can download it from the official website: https://www.python.org/downloads/
Open a terminal or command prompt window on your computer.
Create a new directory where you want to save PlatoGPT. You can do this by typing mkdir PlatoGPT and pressing Enter.
Change to the new directory by typing cd PlatoGPT and pressing Enter.
Clone the PlatoGPT repository from GitHub by typing git clone https://github.com/antiquesordo/PlatoGPT.git and pressing Enter.
Change to the PlatoGPT directory by typing cd PlatoGPT and pressing Enter.
Install the required libraries by typing pip install -r requirements.txt and pressing Enter.
Usage
Place the files you want to extract text and summarize in the data directory.
Run the app by typing python app.py in the terminal and pressing Enter.
A window will open with three buttons: "Extract Text", "Summarize Text", and "OK".
Click the "Extract Text" button to extract text from all files in the data directory.
Click the "Summarize Text" button to generate summaries of the extracted text using the autogpt library.
The results will be saved as separate text files with the same name as the original files, but with "_summary" added to the end.
Click the "OK" button to close the app and view the results.
That's it! You now know how to install and use PlatoGPT to extract text and generate summaries from various file types.
