# Financial Disclosure AI Analysis

## Overview
This project uses Large Language Models (LLMs) and fine-tuning techniques to simplify SEC financial disclosures into plain-language explanations for non-expert readers.

The system retrieves real SEC filings, processes financial disclosure text, evaluates readability, and compares baseline vs fine-tuned model performance.

---

## Features
- SEC EDGAR API integration
- Financial disclosure extraction
- Plain-language simplification using LLMs
- OpenAI fine-tuning workflow
- Readability scoring
- Investment advice compliance checks
- Baseline vs fine-tuned model comparison

---

## Technologies Used
- Python
- OpenAI API
- SEC EDGAR API
- textstat
- dotenv
- JSONL fine-tuning datasets

---

## How It Works

### 1. SEC Filing Retrieval
The system downloads a real 10-K filing from the SEC EDGAR database.

### 2. Text Processing
Narrative financial disclosure text is extracted and cleaned for analysis.

### 3. Baseline Evaluation
A base GPT model generates simplified explanations for non-expert readers.

### 4. Readability Analysis
Outputs are evaluated using:
- Flesch Reading Ease
- Flesch-Kincaid Grade Level

### 5. Fine-Tuning
Custom training examples are used to fine-tune a language model for improved financial simplification.

### 6. Final Comparison
Baseline and fine-tuned outputs are compared for:
- readability
- neutrality
- investment advice compliance

---

## Key Skills Demonstrated
- Financial NLP
- Fine-tuning LLMs
- AI evaluation pipelines
- SEC API integration
- Prompt engineering
- Readability analytics
- Compliance-aware AI systems

---

## Important Notes

### API Key Setup
Create a `.env` file:

```
OPENAI_API_KEY=your_api_key_here
```

Do NOT upload your `.env` file to GitHub.

---

### Fine-Tuning Warning
Fine-tuning:
- may take time to complete
- may incur API costs
- requires OpenAI fine-tuning access

---

## Example Tasks
- Simplify SEC disclosures
- Explain financial risks in plain language
- Compare AI readability performance
- Detect investment advice violations

---

## Files
- `financial_ai_analysis.ipynb` → main notebook
- `train.jsonl` → fine-tuning dataset
- `README.md` → project documentation
- `requirements.txt` → dependencies

---

## Author
Jeremy Granflaten
