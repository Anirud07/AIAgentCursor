# 🧠 AI Agent CLI – Plan-Act-Observe

A terminal-based AI assistant using OpenAI's GPT to handle queries via a Plan → Action → Observe loop.

## 🔧 Features
- JSON-based reasoning with GPT  
- Runs Linux commands (`run_command`)  
- Easy to extend with more tools  
- Fully CLI interactive

## 🚀 Setup
```bash
git clone https://github.com/yourusername/ai-agent-cli.git
cd ai-agent-cli
pip install openai python-dotenv

Create a .env file with:
OPENAI_API_KEY=your-api-key

Run:
python main.py

