# Cold-Email-Generator
# Cold Email Generator

## Overview

The Cold Email Generator is an AI-powered tool designed to automate the process of creating personalized job application emails or business outreach emails. This project leverages advanced technologies such as LangChain, Groq Llama 3.1, and ChromaDB to extract job requirements, match them with relevant expertise, and generate tailored email drafts, streamlining the job application and client engagement process.

---

## Features

### 1. Job Requirements Extraction
- **Web Scraping**: Scrapes job descriptions from career pages using LangChain's WebBaseLoader.
- **Data Structuring**: Extracts structured information (role, skills, experience) in JSON format using Llama 3.1.

### 2. Personalized Email Generation
- **Dynamic Drafting**: Dynamically generates cold emails tailored to specific job postings or business opportunities.
- **Portfolio Links**: Includes matching portfolio links relevant to the job requirements.

### 3. Portfolio Matching with ChromaDB
- **Vector Database Creation**: Creates a vector database of projects and expertise.
- **Intelligent Retrieval**: Queries the database to retrieve relevant projects based on the job requirements.

### 4. State-of-the-Art AI Integration
- **Language Model**: Utilizes Groq Llama 3.1-70b-versatile for natural language understanding and generation.
- **Professional Output**: Provides high-quality, professional email drafts with adjustable creativity levels.

---

## Tech Stack

- **LangChain**: For workflow automation and job description parsing.
- **Groq Llama 3.1**: Advanced language model for extracting requirements and generating emails.
- **ChromaDB**: Persistent vector database for storing and querying portfolio projects.
- **Python**: Core programming language for implementation.
