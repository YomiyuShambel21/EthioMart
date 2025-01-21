# EthioMart-Amharic-Named-Entity-Recognition

## Overview

EthioMart aims to become the primary hub for all Telegram-based e-commerce activities in Ethiopia. With the rising popularity of Telegram as a platform for business transactions, this project seeks to consolidate multiple independent e-commerce channels into a single, centralized platform. The goal is to provide a seamless experience for customers to explore and interact with various vendors in one place.

## Business Need

With the decentralization of e-commerce channels, both vendors and customers face challenges in product discovery, order placement, and communication. EthioMart plans to develop a system that aggregates real-time data from various Telegram channels, focusing on fine-tuning a Large Language Model (LLM) for Amharic Named Entity Recognition (NER). This will enable the extraction of key business entities such as product names, prices, and locations from shared content.

## Key Objectives

- Real-time data extraction from Telegram channels.
- Fine-tune LLM to extract entities like product names, prices, and locations.

## Data Sources

- **Messages and data** from Ethiopian-based e-commerce Telegram channels.
- Sample data collected from Shageronlinestore link.
- Amharic news labeled NER dataset.

## Knowledge and Skills Required

1. **Text Processing**: Handling Amharic text, tokenization, and preprocessing techniques.
2. **LLM Fine-tuning**: Adapting large language models for Amharic NER tasks.
3. **Model Comparison & Selection**: Evaluating performance using metrics like F1-score, precision, and recall.
4. **Model Interpretability**: Using tools like SHAP and LIME to explain model predictions.

## Outcomes

- A working pipeline for entity extraction from Amharic Telegram messages.
- A performance analysis of different models and their interpretability.
- Insights into how the extracted entities can be used for business intelligence in e-commerce contexts.

## Tasks Overview

### Task 1: Data Ingestion and Preprocessing

- Set up a data ingestion system to fetch messages from multiple Telegram channels.
- Preprocess text and image data for entity extraction.

### Task 2: Labeling Dataset in CoNLL Format

- Label a subset of the dataset in CoNLL format for NER tasks.

### Task 3: Fine-Tuning NER Model

- Fine-tune a Named Entity Recognition model to extract key entities from Amharic messages.

### Task 4: Model Comparison & Selection

- Compare multiple models and select the best-performing one for entity extraction.

### Task 5: Model Interpretability

- Use SHAP and LIME to explain how the NER model identifies entities.


## License

This project is licensed under the MIT License.
