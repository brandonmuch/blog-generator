# 🤖 Blog Generator

A Python application that uses the OpenAI API to automatically generate blog posts on any topic.

## 🛠️ Built With
- Python
- OpenAI API (GPT-3)
- python-dotenv

## 💡 How It Works
1. The user inputs a blog topic
2. The program sends the topic to OpenAI's GPT-3 model
3. GPT-3 generates a full blog post on the topic
4. The blog post is printed to the console

## 🚀 How To Run
1. Install dependencies:
   pip install openai python-dotenv
2. Create a .env file in the root directory and add your OpenAI API key:
   API_KEY=your-api-key-here
3. Run the program:
   python blog_generator.py

## ⚠️ Note
Never share your .env file or expose your API key publicly.
