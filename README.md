# GraphDB-Neo4j

This project is designed for learning purposes and demonstrates how to integrate Neo4j, a graph database, with LangChain, a library for building language models, to analyze movie data. The project is divided into two main parts:

1. Setting up a graph and converting a document into a knowledge graph.
2. Loading external data and converting it into a knowledge graph using Neo4j and Cypher query.

## Table of Contents

- [Setup](#setup)
- [Usage](#usage)
  - [Part 1: Convert Text to Knowledge Graph](#part-1-convert-text-to-knowledge-graph)
  - [Part 2: Load and Query External Data](#part-2-load-and-query-external-data)
- [Learnings](#learnings)

## Setup

Before you begin, ensure you have access to a Neo4j instance and the necessary API keys for LangChain and Groq.

## Usage

### Part 1: Convert Text to Knowledge Graph

1. **Set Environment Variables**
2. **Connect to Neo4j**
3. **Initialize LLM**
4. **Convert Text to Graph Documents**

### Part 2: Load and Query External Data

1. **Load Movie Data into Neo4j**
2. **Query the Graph Database**

For detailed code implementation, please refer to the `GraphDB.ipynb` file in this repository.

## Learnings

### LLMGraphTransformer
I learned how to use the `LLMGraphTransformer` to convert text documents into graph documents, enabling the transformation of unstructured text into structured knowledge graphs.

### Harnessing the Powers of LangChain
LangChain's robust framework allowed me to seamlessly integrate various components, making it easier to build complex workflows involving language models and graph databases.

### Using Groq and Its Open Source Models
Exploring Groq and its open-source models provided insights into leveraging advanced language models for tasks like document conversion and query generation, enhancing the capabilities of my project.

### Neo4j - The Graph Database
Working with Neo4j taught me the power of graph databases in storing and querying interconnected data, making it an excellent choice for building knowledge graphs and performing complex queries efficiently.
