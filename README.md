# AI Interview Agent

An AI-powered mock interview tool that evaluates Data Science interview answers in real-time using Google's Gemini API.

## Overview
This project simulates a Data Science mock interview. It asks a series of technical questions, takes the candidate's answers as input, and uses a Large Language Model (Gemini) to evaluate each response — providing a score out of 10 and constructive feedback, just like a real interviewer would.

## Tech Stack
- Python
- Google Generative AI (Gemini API)
- Google Colab

## How It Works
1. The agent presents a Data Science interview question
2. The candidate types their answer
3. The answer is sent to the Gemini API with a structured evaluation prompt
4. The AI returns a score (out of 10) and detailed feedback
5. After all questions, an overall performance summary is generated

## Features
- Real-time AI-based answer evaluation
- Covers core ML/DS concepts (supervised vs unsupervised learning, overfitting, Random Forest, etc.)
- Automated scoring and final performance verdict
- Secure API key handling using Colab Secrets

## How to Run
1. Get a free Gemini API key from [Google AI Studio](https://aistudio.google.com/apikey)
2. Open the notebook in Google Colab
3. Add your API key to Colab Secrets as `GEMINI_API_KEY`
4. Run all cells and answer the interview questions as prompted

## Author
Sushil Agrahari — B.Tech Data Science, AKTU
