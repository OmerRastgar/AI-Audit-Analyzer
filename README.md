# AI-Audit-Analyzer

Transform your policy review process with AI-powered analysis for cybersecurity compliance.

## Overview

AI-Audit-Analyzer automates the compliance review process by leveraging AI to analyze security controls against organizational policies. The tool integrates with Ollama and utilizes embeddings to enhance control mapping and generate detailed compliance insights.

## Features

- **Automated Control Analysis** – Uses DeepSeek model via Ollama to define security controls.  
- **Intelligent Policy Mapping** – Converts policies into embeddings for efficient search and retrieval.  
- **AI-Powered Compliance Reports** – Generates responses for each control based on relevant policies.  
- **Seamless Integration** – Runs as a standalone Python application with minimal setup.  

## Installation

### Prerequisites

Ensure you have the following installed:

- **Windows OS**
- **Python 3.10+**
- **[Ollama](https://ollama.ai/)**
- **pip (Python Package Manager)**

### Setup Instructions

1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-repo/ai-audit-analyzer.git
   cd ai-audit-analyzer

2. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
3. **Run the Application**
   ```sh
   python app.py

### How It Works
The tool iterates through a cybersecurity compliance checklist.
It queries the DeepSeek model via Ollama to define each control.
Policies are converted into embeddings for similarity-based search.
Matching policies and control details are fed back into Ollama for response generation.
The AI-generated responses are appended to the checklist for final review.
Contributing
We welcome contributions! Feel free to submit pull requests or report issues.

### License
This project is licensed under the MIT License.



