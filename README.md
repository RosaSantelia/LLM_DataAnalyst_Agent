# LLM_DataAnalyst_Agent
AI Agent Project for Data Analysis with LLM 

# DataBuddy: Interactive ERP Sales Analyst 🤖

**Ask your ERP sales data a question — get instant answers. Powered by Python + LLM**

## 🚀 What is DataBuddy?

DataBuddy is a natural language assistant that helps you explore ERP sales data (CSV) with simple questions like:

- "What's the most sold product?"
- "Total revenue?"
- "Sales by region?"
- "Top product in March?"

Built with Python and `transformers` (FLAN-T5), it turns your questions into real insights.

## ⚙️ How It Works

1. Loads your ERP sales CSV
2. Uses a lightweight LLM to understand your prompt
3. Matches the intent to a data operation
4. Returns the result with a friendly message

Install dependencies:

```bash
pip install pandas transformers
