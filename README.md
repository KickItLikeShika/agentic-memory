# Agentic Memory

A repo for experiments about different Agentic Memory systems for LLM agents to store, recall, and utilize episodic memories from past conversations, enabling more contextually aware and effective interactions.

## Overview

This project implements an working and episodic memory system for Open-Source LLM-based agents, by utilizing the very recent `gemma-3-1b` LLM.

1. Capturing conversations between users and AI agents
2. Using reflective AI capabilities to extract key insights from each conversation
3. Storing these insights as structured memories in a vector database (Weaviate)
4. Retrieving relevant memories for new conversations based on similarity
5. Incorporating these memories into the agent's context to improve responses

## Features

- **Conversation Reflection**: Automatically extract key insights, patterns, successful strategies, and things to avoid from conversations
- **Semantic Search**: Find similar past conversations using vector similarity
- **Memory Management**: Organized storage of conversation memories in Weaviate

## Components

- **Weaviate**: Vector database for storing and retrieving conversation memories
- **Ollama**: Local embedding and LLM provider
- **LangChain**: Framework for working with LLMs and memory systems

## Notes
This project is mainly inspired by Adam Lucek's work here: https://github.com/ALucek/agentic-memory
