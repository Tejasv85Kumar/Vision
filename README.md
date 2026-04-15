# Vision: AI Assistant

This project is a Python-based AI assistant named Vision. It integrates various APIs and libraries to provide functionalities such as speech recognition, text-to-speech, real-time web searching, and automated system commands through a graphical user interface.

**Project Overview**
Vision is designed to act as an interactive digital assistant that can handle natural language queries. The system processes user input via microphone or text, determines the appropriate action—such as searching the web, opening applications, or engaging in a conversation—and provides both visual and auditory responses.

**Key Features**

Speech Interaction: Includes built-in Speech-to-Text and Text-to-Speech capabilities for hands-free operation.


Real-time Search Engine: Capable of performing live web searches to provide up-to-date information.


Automation: Supports automated commands for common tasks like opening or closing applications, searching Google, and playing media on YouTube.


Graphical User Interface: Features a custom-built GUI for monitoring assistant status and viewing chat history.


Multi-Layered Intelligence: Uses a decision-making model to categorize queries and route them to the correct functional module.

Utilities: Employs tools like PyWhatKit for YouTube automation, AppOpener for system control, and Tavily for advanced search capabilities.

**Setup and Installation**
Prerequisites
Python 3.10

A stable internet connection for API communication 

Environment Configuration
The assistant requires an environment file to store sensitive API keys and user preferences. Create a file named .env in the root directory with the following variables:

CohereAPIKey

GroqAPIKey

HuggingFaceAPIKey

Username

Assistantname
