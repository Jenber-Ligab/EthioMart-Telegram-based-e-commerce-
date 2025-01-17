# EthioMart-Telegram-based-e-commerce-
## **Telegram Data NER Labeling and Tokenization Project**
This project involves extracting named entities such as locations, prices, and products from messages obtained from a 30 Telegram channels and tokenizing the dataset for further analysis. The workflow utilizes a combination of pre-trained Named Entity Recognition (NER) models, custom rule-based labeling techniques, and tokenization for Amharic and multi-lingual text data.
**Project Folder Structure as template**
```|   .gitignore
|   ProjectFolderStr.txt
|   README.md
|   requirements.txt
|   
+---.github
|   \---workflows
+---.vscode
|       settings
|       
+---notebooks
+---scripts
|       __init__.py
|       
+---src
|       __init__.py
|       
\---tests
        __init__.py
```

## **Main Components**
**1. Data Preprocessing**
The raw text data is cleaned and preprocessed. It contains a mix of languages (English and Amharic), but mostly amharic and the data is prepared for tokenization.

**2. Tokenization**
Tokens are generated using AmharicSegmenter method, which segments the text into smaller units (tokens). The tokens are displayed for verification and analysis.
