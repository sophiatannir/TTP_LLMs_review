# Challenges and Applications of Large Language Models

This repository contains a presentation on the challenges and applications of Large Language Models (LLMs) based on the paper by Jean Kaddour, Joshua Harris, Maximilian Mozes, Herbie Bradley, Robert Raileanu, and Robert McHardy. Read the full paper here: [Challenges and Applications of Large Language Models](https://arxiv.org/abs/2307.10169)

## Table of Contents

- [Introduction](#introduction)
- [LLM Challenges](#llm-challenges)
  - [Design Challenges](#design-challenges)
  - [Behavioral Challenges](#behavioral-challenges)
  - [Scientific Challenges](#scientific-challenges)
- [Applications of LLMs](#applications-of-llms)
- [Code Demo](#code-demo)
- [Critical Analysis](#critical-analysis)
- [Discussion and Q&A](#discussion-and-qa)
- [Citation](#citation)

## Introduction

The presentation discusses the rapid advancements in natural language processing (NLP) capabilities, such as GPT-3, PaLM, ChatGPT, and Gemini. The purpose of the paper is to identify open problems and review applications and challenges related to LLMs.

## LLM Challenges

The paper groups challenges into three areas:
1. Design: decisions taken before deployment
2. Behavior: challenges that occur during deployment
3. Science: challenges that hinder academic progress

### Design Challenges

- Unfathomable Datasets
- Tokenizer Reliance
- High Pre-Training Costs

### Behavioral Challenges

- Prompt Brittleness
- Misaligned Behavior
- Outdated Knowledge

### Scientific Challenges

- Brittle Evaluations
- Reliance on Static Human Evaluations
- Lacking Experimental Designs

## Applications of LLMs

### Chatbots

- **Constraints**: 
  - Maintaining dialog coherence over multiple turns.
  - High latency in responses.

### Computational Biology

- **Main Focus**: Protein sequence modeling and prediction.
- **Challenges**: 
  - Transfer to downstream tasks like drug design remains difficult.

### Computer Programming

- **Applications**: 
  - Code generation, completion, and review.
- **Key Constraint**: 
  - Incorporating long-range dependencies across code bases.

### Creative Work

- **Fields**: Story, script, and text generation.
- **Limitation**: 
  - Limited context window requires modular prompting strategies.

### Knowledge Work

- **Constraints**: 
  - Quantitative reasoning.
  - Risk of hallucinations.

### Law

- **Focus Areas**: 
  - Prediction, comprehension, and text generation.
- **Central Challenge**: 
  - Outdated information.

### Medicine

- **Uses**: 
  - Question answering, information extraction, diagnosis, etc.
- **Primary Constraints**: 
  - Hallucinations and biases.

### Reasoning

- **Assistance Areas**: 
  - Mathematical, common sense, and causal reasoning.
- **Performance**: 
  - Remains below human levels on many tasks.

### Robotics

- **Applications**: 
  - Instruction following and planning.
- **Limitation**: 
  - Reliance on single modalities limits capabilities.

### Social Sciences

- **Purpose**: 
  - Simulating human behavior and analyzing model psychology.
- **Requirement**: 
  - Mitigating social biases.


## Code Demo

A code demo is available in the repository: [Code Demo](https://github.com/sophiatannir/TTP_LLMs_review/blob/main/LLM_review.ipynb)

## Critical Analysis

- What was overlooked by the authors?
- What could have been developed further?
- Were there any errors?
- Have others disputed the findings?

## Discussion and Q&A

The presentation includes a section for discussion and Q&A, with possible discussion questions.

## Citation

Kaddour, J., Harris, J., Mozes, M., Bradley, H., Raileanu, R., & McHardy, R. (2023, July 19). Challenges and applications of large language models. arXiv.org. https://arxiv.org/abs/2307.10169
