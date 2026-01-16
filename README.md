# Semantic Book Recommender (NLP)

End-to-end semantic book recommendation system using embeddings + vector search, with category and emotion-based filtering in a Gradio dashboard.

## What it does
- Takes a natural language query (example: "mystery thriller with detective")
- Retrieves similar books using semantic embeddings + vector search
- Supports category filtering and emotion-based sorting
- Displays results in an interactive Gradio dashboard

## Tech used
- Python, Pandas
- OpenAI embeddings + ChromaDB
- Hugging Face Transformers
- Gradio

## Project steps (notebooks)
1. Data exploration: `step1_data_exploration.ipynb`
2. Vector search: `step2_vector_search.ipynb`
3. Text classification: `step3_text_classification.ipynb`
4. Emotion analysis: `step4_sentiment_analysis.ipynb`
5. Gradio dashboard: `gradio_dashboard-step5.ipynb`

## Results
- Cleaned dataset from 6,810 records to 5,197 high-quality entries.

## How to run
This repo currently contains the full pipeline as Jupyter notebooks.
Packaging into a single runnable app (requirements.txt + app.py) is in progress.

## Report
See `Final Report.pdf`
