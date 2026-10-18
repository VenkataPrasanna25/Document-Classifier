# LLM-Based Document Classifier

## Overview
An AI-powered document classification system that uses OpenAI models through a Large Language Model (LLM) to analyze document content and categorize documents automatically. This project explores the practical application of Generative AI for intelligent document processing and automation.

## Features
- Automated document classification using LLMs.
- AI-driven document content analysis.
- Integration with OpenAI models.
- Python-based implementation using a virtual environment.
- Secure API key management using environment variables.

## Technologies Used
- Python
- OpenAI Models
- Large Language Models (LLMs)
- Python Virtual Environment (`venv`)
- Python environment variables (`.env`)

## Project Structure

```text
LLM-Based-Document-Classifier/
│
├── Agent.py
├── Sample_LLM.py
├── Requirements.txt
├── README.md
├── LICENSE
├── .gitignore
└── .gitattributes
```

### File Description

- **Agent.py** — Python file for the agent implementation.
- **Sample_LLM.py** — Python file for the sample LLM implementation.
- **Requirements.txt** — Lists the Python dependencies required by the project.
- **README.md** — Project overview, installation instructions, and usage guide.
- **LICENSE** — Specifies the terms under which others can use your project.
- **.gitignore** — Specifies files Git should ignore.
- **.gitattributes** — Defines Git attributes for repository files.  

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/VenkataPrasanna25/Document-Classifier.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Document Classifier
   ```
3. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   ```
   Windows:
   ```bash
   venv\Scripts\activate
   ```
4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Create a `.env` file based on `.env.example` and add your own OpenAI API key.
6. Run the program
7. python agent.py

## Usage
1. Activate the virtual environment.
2. Ensure your environment variables are configured.
3. Run the Python application using the appropriate entry-point script.
4. Provide a document as input and view its predicted category.

## Security
API keys and sensitive environment variables should never be committed to the repository. The `.env` file is excluded using `.gitignore`.

## Future Improvements
- Support additional document formats.
- Improve classification accuracy and category customization.
- Add a user-friendly interface.
- Support batch document classification.

## License
MIT License (if selected for this repository).
## Project Demo

Here is a sample output of the LLM-Based Document Classifier.

![Document Classifier Output](Document Clasiifier.PNG)

Sample input:
Watching 'E:\DocumentClassifier(AgentVerse)\inbox/' ... drop files in. Ctrl+C to stop.
Sample output:
New file: sample_purchase_requisition.pdf
  extracted 1685 characters
  LLM suggested: 'Purchase Requisitions' - The document is a purchase requisition form used for internal procurement requests, not an invoice.
  -> moved to E:\DocumentClassifier(AgentVerse)\Sorted\Purchase Requisitions\sample_purchase_requisition.pdf

