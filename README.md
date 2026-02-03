# Traffic-congestion
Agentic AI System for Explainable Traffic Congestion Analysis

An AI-powered, explainable traffic intelligence system built using IBM watsonx.ai, IBM Granite foundation models, and Langflow.

The system goes beyond congestion detection by reasoning over traffic data, identifying root causes, and generating human-readable explanations through an agent-based AI architecture.

## Problem Statement

Traditional traffic systems can detect congestion but fail to explain why it occurs, forcing operators to rely on manual interpretation and intuition.
There is a need for an explainable AI system that not only identifies congestion but also provides transparent, trustworthy insights to support faster and more confident traffic decision-making.

## System Architecture

The solution follows a modular, multi-agent architecture, where each agent performs a clearly defined reasoning task.
The workflow is visually orchestrated using Langflow and powered by IBM watsonx.ai Granite models. 

### Model 1 — Traffic Data Analysis Agent
- Analyzes traffic data to detect congestion indicators and patterns
- Identifies anomalies and abnormal traffic conditions

### Model 2 — Congestion Cause Analysis Agent
- Performs causal reasoning to determine underlying congestion causes
- Correlates traffic behavior with time, incidents, and traffic volume changes

### Model 3 — Explainable Insight Generator
- Converts analytical outputs into human-readable explanations
- Ensures transparency and interpretability for end users

## Technology Stack
- IBM watsonx.ai – Enterprise AI platform for running foundation models
- IBM Granite Foundation Models – Instruction-tuned models for explainable reasoning
- Langflow – Visual orchestration of agentic AI workflows

  
## Key Highlights
- Agentic AI architecture instead of a monolithic model
- Explainability-first design aligned with Responsible AI principles
- Human-readable insights for decision-makers
- IBM-native technology stack suitable for public-sector deployment


## Disclaimer

This project is developed for educational and demonstration purposes only and does not provide real-time traffic control or operational decision-making in live city environments.




