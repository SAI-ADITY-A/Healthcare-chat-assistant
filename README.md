# Healthcare Chatbot

## Description
The Healthcare Chatbot is an advanced conversational AI application designed to assist users with health-related inquiries, symptom diagnosis, and general medical information. Leveraging the **Llama 2** language model, this chatbot provides accurate and contextually relevant responses to user questions. The system uses **Qdrant** for efficient vector similarity search, enabling fast retrieval of information from an extensive medical knowledge base.

## Key Features
- **Natural Language Processing (NLP):** Utilizes Llama 2 for understanding and generating human-like responses.
- **Data Chunking and Embeddings:** Processes and stores medical data in chunks to improve retrieval efficiency and relevance.
- **Dynamic Knowledge Retrieval:** Employs Qdrant to index embeddings and perform similarity searches for relevant medical knowledge, enhancing response accuracy.
- **Encyclopedic Knowledge Base:** Integrates a comprehensive medical encyclopedia, allowing the chatbot to provide fact-based responses.

## Technologies Used
- **Llama 2:** Language model for natural language understanding and response generation.
- **Qdrant:** Vector database for managing embeddings and performing similarity searches.
- **NLP Libraries:** SpaCy, NLTK for preprocessing and understanding user queries.
- **Python:** Primary programming language for developing the application.
- **Flask:** Framework for creating the web-based interface.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd healthcare-chatbot
