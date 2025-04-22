# Automated News Summarizer for Mahakumbh

A Natural Language Processing (NLP) project to generate concise, high-quality summaries of Indian news articles related to Mahakumbh. The system uses advanced Transformer-based models for abstractive summarization, enabling efficient information retrieval from large volumes of event-specific content.

    Developed as part of the coursework for CS563: Natural Language Processing at IIT Patna.

## Problem Statement

During events like Mahakumbh, the influx of daily news can be overwhelming. This project addresses the challenge of automatically summarizing Mahakumbh-specific news articles to help readers quickly grasp key points without reading full articles.
## Motivation

    High news volume: Numerous daily updates during the Mahakumbh.

    Information overload: Manual reading is time-consuming.

    Lack of domain-specific tools: Existing summarization tools are generic and not optimized for event-centric news.

## Project Workflow
### 1. Dataset Collection

    Collected 1050 news articles related to Mahakumbh from Google News.

    Utilized the ScrapingDog API with AI-generated prompts to extract clean and structured article content.

### 2. Dataset Annotation

    Created ground-truth summaries (~100 words) per article using LLM-generated outputs.

    Prompt used:
    “Summarize the following news article in 100 words or less.”

    Final format: CSV file with article and summary pairs.

### 3. Model Development

    Fine-tuned Transformer-based models (e.g. Flan t5 base, Gemma, BART, Pegasus, LED) for abstractive summarization.

    Performed evaluation using metrics such as:

        ROUGE-1, ROUGE-2, ROUGE-L

        BLEU Score 
## Contributors

    Sreya Gunda (2101AI15)

    Ishani Sharma (2101AI16)

    Mamta Kanwar (2101CS42)
