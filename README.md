# Text-to-SQL Generator

A Jupyter notebook that converts plain English questions into SQL queries using Claude AI (Anthropic).

## What it does
- Type a question in plain English (e.g. "Show me top 5 customers by revenue")
- The AI generates a clean, production-ready SQL query instantly
- Supports streaming output — watch the SQL appear in real time
- Built-in interactive widget UI inside JupyterLab

## Tech Stack
- Python
- Anthropic Claude API (claude-sonnet)
- ipywidgets
- JupyterLab

## How to run

1. Clone the repository
   git clone https://github.com/shambhuhiwase/Text-to-SQL-Generator.git

2. Install dependencies
   pip install anthropic ipywidgets

3. Set your API key
   export ANTHROPIC_API_KEY="your-api-key-here"

4. Open the notebook in JupyterLab and run the cell

## Sample Questions to Try
- Top 5 customers by total spending in the last 30 days
- Monthly revenue totals for the last 12 months
- All products with stock less than 10
- Pending orders older than 7 days

## Author
Shambhu Hiwase
