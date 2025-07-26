# ApplicantCentral (System for Tracking Applications) 

## Overview

The Application Tracking System (ATS) is designed to automate the resume screening process by analyzing job descriptions and candidate resumes to provide a relevance score. By leveraging natural language processing (NLP) and machine learning techniques, the system enhances recruitment efficiency by reducing manual effort and ensuring an objective candidate evaluation process.

## Features

- **Resume Parsing:** Extracts text from PDF and DOCX resumes.
- **Text Preprocessing:** Tokenizes, removes stopwords, and lemmatizes text for better analysis.
- **Similarity Calculation:** Uses TF-IDF vectorization and cosine similarity to rank resumes.
- **Employer Mode:** Enables recruiters to input job descriptions for candidate evaluation.
- **Candidate Mode:** Allows applicants to submit resumes and receive relevance scores.
- **Jupyter Notebook-Based Interface:** Provides an interactive and structured environment for execution.

## Tech Stack

- **Python** – Core programming language used for processing and logic.
- **Jupyter Notebook** – Provides an interactive interface for executing the ATS system.
- **PyPDF2 & python-docx** – Extracts text from PDF and DOCX resume files.
- **NLTK (Natural Language Toolkit)** – Handles text tokenization, stopword removal, and lemmatization.
- **Scikit-learn** – Implements TF-IDF vectorization and cosine similarity for ranking resumes.
- **Pyfiglet & Termcolor** – Enhances CLI output with ASCII formatting and color styling.
- **OS Module** – Manages file handling operations.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/ApplicantCentral-Application-Tracking-System-main.git
   cd ApplicantCentral-Application-Tracking-System-main
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter Notebook:
   ```sh
   jupyter notebook ATS.ipynb
   ```
2. Run the notebook cells sequentially.
3. Choose `Employer Mode` to input job descriptions or `Candidate Mode` to evaluate resumes.
4. Follow the on-screen prompts to analyze resume relevance scores.

## Contribution

Contributions are welcome. To contribute:

- Fork the repository.
- Create a new branch.
- Commit your changes.
- Submit a pull request.




