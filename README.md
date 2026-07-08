## Project Title : Enterprise Document AI
    Enterprise-grade PDF Question Answering system built with Python, Flask, OpenAI GPT, and Slack integration.

## Project Overview: 
    An AI-powered document intelligence platform that extracts text from PDF documents and answers natural language questions using Large Language Models (LLMs).

    The system processes large documents efficiently by chunking content, querying an LLM, aggregating responses, and returning structured JSON output. It also integrates with Slack for automated notifications.

    This project demonstrates practical experience in AI application development, REST APIs, document processing, and LLM integration.

## Architecture:
                                               User
                                                │
                                                ▼
                                        REST API (Flask)
                                                │
                                                ▼
                                        PDF Text Extraction
                                                │
                                                ▼
                                        Text Chunking
                                                │
                                                ▼
                                            OpenAI GPT
                                                │
                                                ▼
                                        Response Aggregation
                                                │
                                                ▼
                                            JSON Output
                                                │
                                                ▼
                                            Slack API
## Features:
    - 📄 Extracts text from PDF documents using PyMuPDF.
    - 🤖 Answers natural language questions using OpenAI GPT.
    - 📚 Automatically splits large documents into manageable chunks.
    - 🔍 Processes multi-page PDFs efficiently.
    - 📋 Returns answers in a structured JSON format.
    - 💬 Posts extracted answers to Slack channels automatically.
    - 🌐 Provides REST APIs for easy integration with other applications.
    - ⚙️ Environment-based configuration using `.env` files.
    - 🚨 Includes error handling for invalid PDFs and API failures.
    - 📦 Modular project structure for easy maintenance and scalability.

## Technology Stack
                    | Technology | Purpose                  |
                    | ---------- | ------------------------ |
                    | Python     | Backend language         |
                    | Flask      | REST API                 |
                    | OpenAI GPT | Question answering       |
                    | PyMuPDF    | PDF text extraction      |
                    | Slack API  | Notifications            |
                    | dotenv     | Configuration management |
                    | JSON       | Response format          |
## Skills Use: 
    - Python
    - Flask
    - REST APIs
    - OpenAI API
    - Prompt Engineering
    - Document Processing
    - AI Application Development
    - JSON Processing
    - Slack Integration
    - Error Handling
    - Configuration Management

## Project Workflow:
    1. Upload or select a PDF.
    2. Extract text using PyMuPDF.
    3. Split large documents into chunks.
    4. Send each chunk with the user question to the LLM.
    5. Aggregate responses.
    6. Return structured JSON.
    7. Post the result to Slack.

## 📁 Project Structure:
    Enterprise-Document-AI/
    │── app/
    ├── api/
    ├── services/
    ├── utils/
    ├── config.py
    ├── server.py
    ├── requirements.txt
    ├── .env.example
    ├── README.md
    └── sample.pdf

## API Endpoints
     POST /ask

## Example Request:
    POST /ask
    {
    "question": "What is the policy number?"
    }

## Example Response
    {
    "Policy Number": "123456"
    }

## Challenges Solved:
    1. Managed LLM context limits by implementing text chunking.
    2. Aggregated responses from multiple chunks.
    3. Prevented hallucinations by returning "Data Not Available" when information was missing.
    4. Integrated Slack notifications for automated sharing.

## Future Enhancements
    1.  Retrieval-Augmented Generation (RAG)
    2. Vector database integration (FAISS, Pinecone, ChromaDB)
    3. Embeddings
    4. OCR for scanned PDFs
    5. Streaming responses
    6. Authentication
    7. Docker and Kubernetes deployment
    8. AWS/Azure deployment
    9. CI/CD pipeline
    10. Monitoring and logging

## 🚀 Installation
    git clone https://github.com/kamalakanta09/enterprise-document-ai.git
    cd enterprise-document-ai
    pip install -r requirements.txt

## ⚙️ Environment Variables:
    Create a `.env` file.
    ```env
    OPENAI_API_KEY=your_api_key
    SLACK_BOT_TOKEN=your_token
    SLACK_CHANNEL=#general
    ```

## 👨‍💻 Author: **Kamalakanta**

    TL/Backend & AI Developer

### Skills
    - Python
    - FastAPI
    - Flask
    - Node.js
    - React
    - AWS/ Azure
    - AWS Bedrock
    - Microservices
    - Event-Driven Architecture
    - Kafka
    - RabbitMQ
    - Docker
    - SQL & NoSQL
    - AI & LLM Applications

### Connect with me
- GitHub: https://github.com/kamalakanta09
- LinkedIn: https://www.linkedin.com/in/kamala-kant-158520279/?skipRedirect=true
- Email: kamala.igit@gmail.com