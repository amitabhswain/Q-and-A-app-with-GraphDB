# Q&A application with GraphDB

This project demonstrates the integration of Graph Databases (Neo4j) with LangChain to create an intelligent question-answering system. The system allows users to query a movie database using natural language, which gets converted to Cypher queries through LLM processing.

# Key Features

• Connects Neo4j Graph Database with LangChain
• Uses Grok LLM for natural language processing
• Converts natural language questions to Cypher queries
• Supports complex queries about movies, actors, and directors
• Implements few-shot prompting strategies for better query generation

# Technical Components

**Database Setup**

• Neo4j AuraDB as the graph database
• Movie dataset with relationships between movies, actors, directors, and genres

**Core Dependencies**
• langchain_community
• langchain_grok
• neo4j
• python-dotenv

**Architecture**

• User submits natural language query
• LLM processes query and generates Cypher statement
• Graph database executes Cypher query
• System formats and returns response


# Example Queries
• Find movie directors
• List actors in specific movies
• Count movies by actor
• Query movie genres
• Find relationships between actors and directors

The project serves as a practical demonstration of combining graph databases with modern LLM capabilities for intelligent data querying.
