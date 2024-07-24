# FitBot: Your AI Fitness Companion(RAG) 🏋️‍♀️💪

Harness the power of Retrieval-Augmented Generation (RAG) to create a smart, context-aware fitness assistant. This project demonstrates how to build a chatbot that combines the latest in language modeling with specialized fitness knowledge.

## Project Overview

FitBot is an AI-powered chatbot designed to provide personalized fitness advice, leveraging:

- Zephyr LLM for natural language understanding and generation
- all-MiniLM-L6-v2 for efficient document embedding
- THE COMPLETE FITNESS HANDBOOK as a comprehensive knowledge base

## The Magic of RAG

RAG technology allows FitBot to:
1. Understand your fitness queries
2. Search its vast knowledge base for relevant information
3. Formulate expert-level responses tailored to your needs

This means you get the benefits of both broad AI capabilities and specific fitness expertise!

## Getting Started

### Prerequisites
- Python 3.6+
- Hugging Face account
- THE COMPLETE FITNESS HANDBOOK (PDF format)

### Quick Setup

1. Clone and navigate:
   ```
   git clone https://github.com/GurakaranSingh374/fitbot.git
   cd fitbot
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Add your fitness handbook:
   - Rename your PDF to `fitnesshandbook.pdf`
   - Place it in the project root directory

4. Launch FitBot:
   ```
   python app.py
   ```

5. Open the provided URL in your browser and start chatting!

## Customization Options

Make FitBot your own:

- Swap out `fitnesshandbook.pdf` for any fitness-related PDF
- Adjust the `system_message` in `app.py` to change FitBot's personality
- Experiment with different Hugging Face models
- Add new example queries to showcase FitBot's capabilities

## Deployment: Share Your FitBot

Take FitBot live with Hugging Face Spaces:

1. Fork this repo
2. Create a new Space on [Hugging Face](https://huggingface.co/spaces)
3. Select Gradio as your SDK
4. Connect your forked repo
5. Upload your `fitnesshandbook.pdf`
6. Launch and share your FitBot with the world!

## Important Note

FitBot is a fun and informative AI assistant, but it's not a replacement for professional medical or fitness advice. Always consult with qualified experts for your health and fitness needs.

## Join the FitBot Community

- Found a bug? Have an idea? Open an issue or submit a PR!
- We're excited to see how you'll enhance FitBot

## Get in Touch

Questions? Ideas? Reach out at gu4378374@alphacollege.me

Happy Fitness Journey with FitBot! 🏃‍♂️🤖
```
