# AI-Voice-Support-Bot-CLI-Version-

# AI Voice Support Bot (CLI Version)

This project is a **Command-Line Interface (CLI)** application that demonstrates an **AI-powered Voice Support Bot** built using **Dia-1.6B** from Hugging Face. The bot listens to user input, generates a text-based response, and converts it into realistic speech using a **Text-to-Speech (TTS)** model. The goal is to simulate a voice assistant for customer support scenarios.

## Features

- **Text-to-Speech Conversion**: Converts AI-generated text responses into speech.
- **Customizable Responses**: The bot can be easily customized to respond to different queries (e.g., order status, refund requests).
- **CLI Interface**: Simple command-line interaction for testing and development.

## Requirements

- **Python 3.7+**
- **Hugging Face's Dia-1.6B model**
- **Gradio** (if you plan to add a GUI interface)

### Libraries to Install

Before running the application, ensure you have the necessary Python libraries installed:

```bash
pip install transformers torch soundfile gradio
