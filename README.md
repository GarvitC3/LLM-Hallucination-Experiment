# LLM Hallucinations Experiment

This repository contains the results of a hallucination experiment comparing two large language models (LLMs): **Claude 3** and **Gemini 1.5**.

## Objective
To evaluate which model hallucinates more in a government contracting context and test mitigation strategies to reduce hallucinations.

## Structure
- `prompt_results.csv`: Logs each prompt, model used, mitigation strategy, and hallucination outcome.
- `screenshots.pdf`: Document for LLM response screenshots with screenshots for each prompt and mitigation techniques

## Prompt Mitigation Strategies
1. Add a disclaimer: "If unsure, say 'I don’t know.'"
2. Ask for citations
3. Break the prompt into smaller parts

## Why this experiment took place
This was created to test how different LLMs react to fictionary prompts and if they hallucinate fake information. Made for an internship at the defense contracting startup **Sales Patriot**.
