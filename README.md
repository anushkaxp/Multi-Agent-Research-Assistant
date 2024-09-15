# Multi-Agent-Research-Assistant
## Project Overview
The Multi-Agent Research Assistant is designed to assist researchers by automating the process of retrieving, analyzing, and summarizing research papers. The system consists of multiple agents, each responsible for specific tasks such as paper retrieval, information extraction, and summarization. The agents collaborate to deliver concise summaries of research papers based on user input.

## Objectives
 
1) Automated Research Paper Retrieval: Agents fetch papers from databases like arXiv using specific search queries.
2) Text Extraction: Agents extract relevant sections such as titles, abstracts, keywords, conclusions, and more.
3) Summarization: Agents create concise summaries of the papers by analyzing their content.
4) Collaboration: Agents communicate to divide and accomplish tasks efficiently.



## Agents in the System

### 1. Retrieval Agent
Role: Searches for research papers using APIs (e.g., arXiv API).
Task: Retrieves papers based on user-defined search queries.

### 2. Text Extraction Agent
Role: Extracts specific sections from the retrieved PDFs, such as titles, abstracts, methods, results, and conclusions.
Task: Processes the text from PDFs to identify relevant sections using pattern recognition techniques.
### 3. Summarization Agent
Role: Summarizes the extracted text into concise overviews.
Task: Uses text summarization algorithms to generate summaries of research papers.
### 4. Collaboration Manager Agent
Role: Coordinates communication between agents.
Task: Ensures that the retrieval, extraction, and summarization agents work together efficiently and synchronously.


## How It Works
User Input: The user provides a query or research topic through the interface.
Paper Retrieval: The Retrieval Agent searches research paper databases using the query and fetches relevant papers.
Text Extraction: The Text Extraction Agent extracts important sections such as the abstract, methods, results, and conclusions from the retrieved PDFs.
Summarization: The Summarization Agent processes the extracted content to create a concise summary of each paper.
Collaboration: The Collaboration Manager Agent ensures that each agent completes its task in sequence.
Display Summary: The system displays the summarized research papers for the user to review.


## Installation & Setup
Prerequisites
-- Python 3.x
Required Libraries
1)pdfplumber
2)requests
3)pandas
4)xml.etree.ElementTree

## Setup Instructions
Clone the repository: "git clone https://github.com/username/multi-agent-research-assistant.git
cd multi-agent-research-assistant"

Install required dependencies:
"pip install -r requirements.txt"


## Usage
1)Start the system by running the main program.
2)Enter a research topic or query.
3)The system will fetch papers, extract relevant information, and generate summaries.
4)The summarized results will be displayed for the user

