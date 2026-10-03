# Agent Communication Framework

A web-based framework for communication between software agents using request and response messages.

## Project Overview

This project demonstrates how multiple agents can communicate through a central communication framework. Agent-A sends a request, the framework forwards it to Agent-B, and Agent-B processes the request and generates a response.

## Communication Flow

Agent-A → Communication Framework → Agent-B

Agent-B → Communication Framework → Agent-A

## Features

* Agent-to-agent communication
* Request and response mechanism
* Automatic response generation
* Communication log
* Request IDs
* Timestamps
* Agent status monitoring
* Web-based dashboard
* Communication statistics

## Technologies

* Python
* Flask
* Flask-CORS
* HTML
* CSS
* JavaScript
* Google Colab
* ngrok

## Agents

**Agent-A:** Request-generating agent.

**Agent-B:** Processing and response agent.

## How It Works

1. Agent-A creates a request.
2. The request is sent to the communication framework.
3. The framework forwards the request to Agent-B.
4. Agent-B processes the request.
5. Agent-B generates a response.
6. The response is returned to Agent-A.
7. The communication is displayed in the web dashboard.

## Running the Project

The complete implementation is available in the Google Colab notebook:

`Agent_Communication_Framework.ipynb`

Install the required packages using:

```bash
pip install -r requirements.txt
```

The Flask application can then be started through the provided notebook.

## Project Structure

```text
Agent-Communication-Framework/
│
├── Agent_Communication_Framework.ipynb
├── requirements.txt
└── README.md
```

## Note

The live dashboard uses Google Colab and ngrok during demonstration. The ngrok authentication token should never be committed to the repository.
