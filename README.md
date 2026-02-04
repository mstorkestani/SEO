# The Prompt Engineering Library for SEO & GEO

Welcome to the extensive library of prompt engineering techniques for modern marketers. This repository is designed to be a comprehensive, hands-on resource for understanding how different prompting strategies can dramatically alter the quality, structure, and effectiveness of AI-generated content for Search Engine Optimization (SEO) and Generative Engine Optimization (GEO).

## What is This Repository?

This is not a single workshop, but a **living library of prompts**. It contains dozens of examples across multiple techniques, all applied to a consistent case study. Its purpose is to allow students and practitioners to:

1.  **Explore a wide range of prompt engineering techniques.**
2.  **See direct, side-by-side comparisons** of how small changes in a prompt can lead to vastly different outputs.
3.  **Understand when and why to use a specific technique** for a given marketing task.
4.  **Copy and adapt** these prompts for their own projects.

## How to Use This Library

This repository is designed for self-exploration. Each numbered directory represents a different prompt engineering technique. Inside each directory, you will find:

*   A `README.md` file explaining the technique in detail.
*   Subdirectories for different marketing tasks (e.g., `keyword-research`, `content-creation`).
*   Multiple prompt examples (`prompt_1.md`, `prompt_2.md`, etc.) showing different variations of the technique.
*   Corresponding output examples (`output_1.md`, `output_2.md`, etc.) showing the AI's response to each prompt.

**Your task is to explore, compare, and learn.** Ask yourself:

*   *Why* did the output change when the prompt was modified?
*   What new information did the AI have that led to a better result?
*   In what situation would I use the basic prompt versus the advanced one?

For a more detailed guide on how to navigate this library, see `HOW_TO_USE.md`.

## Repository Structure

```
/prompt-engineering-seo-geo-library
├── README.md                       # Main overview (this file)
├── HOW_TO_USE.md                   # Guide to exploring the library
│
├── /case-study
│   └── LEAKEYS_BOOKSHOP.md         # The consistent business case study for all prompts
│
├── /01-zero-shot-prompting
│   ├── README.md
│   └── /...
├── /02-few-shot-prompting
│   ├── README.md
│   └── /...
├── /03-chain-of-thought-prompting
│   ├── README.md
│   └── /...
├── /04-persona-prompting
│   ├── README.md
│   └── /...
├── /05-structured-output-prompting
│   ├── README.md
│   └── /...
├── /06-negative-prompting
│   ├── README.md
│   └── /...
├── /07-retrieval-augmented-generation
│   ├── README.md
│   └── /...
└── /08-meta-prompting
    ├── README.md
    └── /...
```

## The Case Study

All prompts in this library are based on a single, consistent case study: **Leakey's Bookshop** in Inverness, Scotland. This allows for a fair comparison of techniques, as the underlying context never changes. You can learn more about the business in `/case-study/LEAKEYS_BOOKSHOP.md`.

## The Techniques

This library covers a wide range of fundamental and advanced techniques, including:

1.  **Zero-Shot Prompting:** The most basic form of prompting.
2.  **Few-Shot Prompting:** Providing examples to guide the AI.
3.  **Chain-of-Thought (CoT):** Asking the AI to "think step-by-step."
4.  **Persona Prompting:** Assigning a role and personality to the AI.
5.  **Structured Output Prompting:** Forcing the AI to return data in a specific format (e.g., JSON, Markdown table).
6.  **Negative Prompting:** Telling the AI what *not* to do.
7.  **Retrieval-Augmented Generation (RAG):** Providing the AI with external data to work from.
8.  **Meta-Prompting:** Asking the AI to critique and improve its own prompts.

Let the exploration begin!
