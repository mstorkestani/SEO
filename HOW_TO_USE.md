# How to Use This Prompt Library

Welcome to the Prompt Engineering Library for SEO & GEO! This guide will help you get the most out of this resource.

## The Core Idea: Learning by Comparison

This library is built on a simple but powerful idea: the best way to understand prompt engineering is to see the direct impact of different techniques. For every marketing task, you will find multiple prompt examples, from the most basic to the most advanced. By comparing the prompts and their corresponding outputs side-by-side, you will develop an intuitive understanding of how to craft effective prompts.

## Your Learning Workflow

Here’s a recommended workflow for exploring this library:

### Step 1: Choose a Technique

Start by choosing one of the numbered directories, each representing a different prompt engineering technique (e.g., `/01-zero-shot-prompting`, `/02-few-shot-prompting`).

### Step 2: Read the `README.md`

Inside each technique directory, you will find a `README.md` file. Read this first to understand:

*   **What the technique is:** A clear definition and analogy.
*   **When to use it:** The specific situations where this technique excels.
*   **Key characteristics:** What makes this technique unique.

### Step 3: Choose a Marketing Task

Within each technique directory, you will find subdirectories for different marketing tasks (e.g., `keyword-research`, `content-creation`). Choose one that interests you.

### Step 4: Compare the Prompts and Outputs

Inside each task directory, you will find one or more prompt files (`prompt.md`, `prompt_1.md`, etc.) and their corresponding output files (`output.md`, `output_1.md`, etc.).

1.  **Open the prompt file:** Read the prompt carefully. What information is being provided to the AI?
2.  **Open the output file:** See how the AI responded to that specific prompt.
3.  **Compare:** Now, open another prompt and output file in the same directory (or from a different technique directory) and compare them. Ask yourself:
    *   What changed in the prompt?
    *   How did that change affect the output?
    *   Was the output better or worse? Why?

### Step 5: Experiment!

The best way to learn is by doing. Take the prompts from this library and:

*   **Modify them:** Change the wording, add or remove constraints, and see what happens.
*   **Apply them to a different case study:** How would you adapt these prompts for a different business?
*   **Combine techniques:** Can you use a persona prompt and a chain-of-thought prompt together?

## Example Exploration: Keyword Research

Let’s say you want to understand how to generate better keywords. You could follow this path:

1.  **Start with Zero-Shot:** Go to `/01-zero-shot-prompting/keyword-research`. Look at the simple prompt and the generic, unstructured output.
2.  **Move to Few-Shot:** Go to `/02-few-shot-prompting/keyword-research`. See how providing a few examples helps the AI understand the desired style of keywords.
3.  **Advance to Chain-of-Thought:** Go to `/03-chain-of-thought-prompting/keyword-research`. Notice how asking the AI to “think step-by-step” leads to a much more strategic and well-reasoned keyword list, complete with audience segmentation and categorization.

By the end of this exploration, you will have a clear mental model of how to move from a basic keyword request to a sophisticated keyword strategy prompt.

## Key Questions to Ask Yourself

As you explore, keep these questions in mind:

*   **What is the goal of this prompt?** What am I trying to achieve?
*   **What information does the AI need to succeed?** Have I provided enough context?
*   **How can I be more specific?** Are there any ambiguities in my prompt?
*   **What is the ideal format for the output?** Have I specified it clearly?
*   **How can I guide the AI’s reasoning process?** Can I use a technique like CoT?

## A Note on AI Variability

Remember that LLMs are non-deterministic, meaning you might not get the exact same output as the examples in this library, even if you use the same prompt. **This is normal.** The goal is not to replicate the outputs perfectly, but to understand the *principles* that lead to better outputs. Focus on the *change in quality* between the different techniques, not on matching the exact wording.

Happy exploring!
