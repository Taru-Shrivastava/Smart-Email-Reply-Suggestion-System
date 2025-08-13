# Smart Email Reply Suggestion System
A system to generate polite email replies using fine-tuned DistilGPT-2 with QLoRA.

## Setup
1. Create virtual env: `python -m venv email_reply_env`
2. Activate: `email_reply_env\Scripts\activate` (Windows)
3. Install: `pip install -r requirements.txt`
4. Datasets: Enron (Kaggle), Avocado (LDC), Politeness (GitHub).

## Notes
- GPU: 2GB (or CPU fallback).
- Avocado dataset pending LDC approval.