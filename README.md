
# Problem Statement

To create a Document Summarizer using pipeline which can handle document of any format. Also to add pipeline for QnA. 

# Document Summarizer

The doc summarizer can take input of pdf, text, img and convert it into a summary. It has also feature of Question Answering and translation of text.

## Installation
To get started with the project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/document-summarizer.git
cd document-summarizer
pip install -r requirements.txt
```


## Features

Document Summarization: Summarizes large documents into concise summaries using `microsoft/Phi-3-mini-128k-instruct`.

Translation: Translates text into Hindi using `googletrans()`.

Question Answering: Answers questions based on document content using `deepset/roberta-base-squad2`.



## Hosting

```bash
streamlit run app.py

ngrok http 8501
```
    
## Contributions

Jeel Savsani, Prakrut Moon, Yanshik Jada, Yash Dodiya, Arnav Deshpande




## Demo Video and Report

video link: https://drive.google.com/file/d/1HtBseEKWRSSkWoOF55zxgdNTP_911rYC/view?usp=sharing 

Report link: https://docs.google.com/document/d/1wgHxrRYpgwQ7mu4dB4HXAwyy4bE5EsPIEki4E_haft0/edit?usp=sharing



## Acknowledgements

 - Summarization Model: [microsoft/Phi-3-mini-128k-instructs](https://huggingface.co/microsoft/Phi-3-mini-128k-instruct)
 - Question Answering Model: [deepset/roberta-base-squad2](https://huggingface.co/deepset/roberta-base-squad2)
 - Translation Tool: [googletrans](https://pypi.org/project/googletrans/)

