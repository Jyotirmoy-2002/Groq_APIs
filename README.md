# Groq_APIs
This repository will give a brief idea about the fundamentals of groq, the models available and their different use cases from api calling to everything
# GroqCloud Model Guide

## Overview
A snapshot of the core AI models provided by GroqCloud, highlighting their distinctions and recommended scenarios.

## Model Categories

### Featured Models
- **openai/gpt-oss-20B**
- **openai/gpt-oss-120B**

### Production Models
- **llama-3.1-8b-instant**
- **llama-3.3-70b-versatile**
- **meta-llama/llama-guard-4-12b**
- **whisper-large-v3**
- **whisper-large-v3-turbo**

### Preview Models (Evaluation Only)
- **deepseek-r1-distill-llama-70b**
- **meta-llama/llama-4-maverick-17b-128e-instruct**
- **meta-llama/llama-4-scout-17b-16e-instruct**
- **moonshotai/kimi-k2-instruct**
- **qwen/qwen3-32b**
- **playai-tts**
- **playai-tts-arabic**
- **openai/gpt-oss-20B** *(Preview)*
- **openai/gpt-oss-120B** *(Preview)*

### Preview Systems
- **compound-beta**
- **compound-beta-mini**

### Tool-Use Specialized Llama 3
- **Llama-3-Groq-70B-Tool-Use**
- **Llama-3-Groq-8B-Tool-Use**

### Llama 3.1 Family
- **Llama 3.1 Instruct 8B & 70B**
- **Llama 3.1 (405B) and variants**

## Use Cases
| Scenario | Recommended Model(s) |
|----------|----------------------|
| General text generation with tool integration | openai/gpt-oss variants, compound systems |
| Fast, reliable production workloads | Production Llama models |
| Audio transcription | whisper-large-v3 variants |
| Tool-calling / function agents | Llama-3-Groq-Tool-Use |
| Long-context tasks, complex workflows | Llama 3.1 family |

