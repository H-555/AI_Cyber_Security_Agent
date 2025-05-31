# AI powered Cyber security Agent using Mistral
It monitors the security logs, detects anomalies and suspicious pattern, classifies the threat level using llm intelligence, validates the threat and suggests response by referring internal threat policies. Continuous monitoring of security data and autonomous action taking without human intervention will be enabled in future.

# Features:
Analyse the security data, detects anomalies and suspicious pattern (Uses RAG).

Classifies the threat level using llm intelligence.

validates the threat and suggests response with internal threat policies (Uses RAG).

# Requirements:
Install the required dependencies:

pip install openai

pip install pyautogen

pip install langchain-community

pip install pandas

# How it Works?
Its has 3 main components:

anomaly_detector - Analyse the security data, detects anomalies and suspicious pattern using RAG.

threat_classifier_agent - Classifies the threat level using llm intelligence.

validator_and_responder_agent - validates the threat and suggests response with internal threat policies using RAG.
