# Financial Report Disclosure Tone Analyzer

This notebook analyzes the textual sections of a company's financial reports to determine the overall tone (positive, negative, neutral) using Generative AI capabilities.

## Overview

This project analyzes the disclosure tone in company financial reports, specifically focusing on sections like the Management's Discussion and Analysis (MD&A). Understanding the sentiment expressed in these reports can provide valuable insights into the company's outlook, potential risks, and overall communication strategy.

**Use Case:**

Manually analyzing the tone of lengthy financial reports is time-consuming and subjective. Generative AI offers powerful tools to automate this process and provide more objective and scalable insights.

**Gen AI Capabilities Demonstrated:**

* Document Understanding (for parsing the reports and identifying sections)
* Sentiment Analysis using Few-Shot Prompting with a Large Language Model
* Embeddings/Vector Search (for quantifying tone and identifying related sentiment-bearing words)
* Structured Output (for presenting results in JSON format)
* Gen AI Evaluation (for evaluating the tone analysis results)

## Setup and Libraries

* Python
* Google Gemini Pro (via `google-genai` SDK)
* PyPDF2
* Sentence Transformers
* Transformers
* Matplotlib

## Usage

1.  **Install dependencies:**

    ```bash
    pip install google-genai PyPDF2 sentence-transformers transformers
    ```
2.  **Set up Google API key:**
    * Ensure you have a Google API key.
    * Use the `google-genai`  SDK to configure your API key.
3.  **Run the notebook:**

    * Follow the code steps to input a financial report PDF. The notebook will extract text, analyze sentiment, and provide a structured output of the tone analysis.

## Project Structure
Financial-Report-Tone-Analyzer/
├── README.md
├── Capstone_Notebook.ipynb
└── data/
    └── sample_report.pdf

## Gen AI Evaluation

The notebook includes an evaluation of the tone analysis using a LLM with few-shot examples, assessing accuracy, relevance, and consistency.

## Conclusion and Next Steps

This notebook demonstrates the use of several Gen AI capabilities to analyze the tone of financial reports.

**Potential Improvements:**

* Improve Document Understanding for more accurate section identification.
* Experiment with larger and more powerful LLMs.
* Fine-tune embedding models on financial text data.
* Use a Long Context Window model for analyzing entire sections.
* Develop more sophisticated methods for identifying nuanced language.
* Visualize tone analysis results.
* Refine tone evaluation prompts and criteria.

## Author

Izuardo Zulkarnain

## Date

April 8, 2025
