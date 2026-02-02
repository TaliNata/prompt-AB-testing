## Model Configuration

- Model: GPT-4o
- Interaction mode: Chat completion
- Temperature: default
- Top-p: default
- Same input text for all runs

# Prompt A/B Testing Case Study

This repository demonstrates an A/B test of two LLM prompts
to evaluate output quality, structure, and stability.

## Goal
Select the most stable and controllable prompt for analytical summarization.

## Method
- Same task
- Same model
- Same input
- 10 runs per prompt
- Qualitative evaluation

## Structure
- `prompts/` – tested prompts
- `results/` – model outputs
- `evaluation.md` – comparison and conclusion

## Key Result
Prompt B showed higher structural consistency and repeatability
and was selected as the production-ready version.

