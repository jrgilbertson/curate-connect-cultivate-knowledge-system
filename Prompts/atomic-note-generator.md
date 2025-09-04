---
aliases: []
date_created: 2025-08-20 15:08
date_modified: 2025-08-30 20:08
tags: []
title: Atomic Note Generator
---

# Atomic Note Generator

## Goal

Generate up to three atomic notes on the provided topic. Each note must capture a single, stand-alone concept suitable for integration into an atomic note system with [[202509010952 Spaced repetition is a learning technique that involves reviewing information at increasing intervals to improve long-term retention|spaced repetition]] flashcards.

## Return Format

Present the final atomic notes, each enclosed in its own markdown code block. Provide up to three notes total.

Each atomic note must have the following fields, with NO leading indentation before each field name or its content, in this exact order:

```python sql
Flashcard Title: (2–5 words)
Question: (a single, non-compound question)
Answer:
    A comprehensive yet concise self-contained explanation (20–60 words), 
    thoroughly covering the core concept. The first sentence must be a 
    clear, stand-alone summary.
    
    A paragraph providing a clear, relatable comparison to illustrate the 
    core concept (no specific length limit).
    
    A real-world example starting with "For example," (no specific length 
    limit).
Extra:
    ## Synonyms
    - [List of alternative terms]

    ## Common Misconceptions
    - [Misconception 1] (Correction: [Correction 1])
    - [Misconception 2] (Correction: [Correction 2])

    ## Cross-Domain Connections
    - [Connection 1]
    - [Connection 2]

    ## Further Exploration
    - [Suggestion 1]
    - [Suggestion 2]

    ## Keywords
    - [Bulleted list of relevant keywords]

    ## Sources
    - [Plain text sources, bulleted if multiple]
```

## Important Guidelines

### Format Requirements

- **Strictly adhere to the specified output format.** Do not include any introductory text, closing remarks, commentary, or reasoning steps in the final atomic note outputs.
- **CRITICAL: Do NOT indent the paragraphs within the 'Answer' section or the content under the 'Extra' headers.** Use line breaks for separation, not tabs or spaces.
- Ensure absolute atomicity: Each atomic note must represent *one* distinct idea.
- Do not include compound questions in the Question field.
- Do not include any bracket links or inline IDs (e.g., `[[...]]`).
- Do not include extra metadata like aliases, dates, or HTML/Obsidian links.

### Mathematical Content

Format all mathematical content using LaTeX:

- Use `$…$` for inline math (e.g., `$E = mc^2$`)
- Use `$$…$$` for display math (e.g., `$$\int_a^b f(x) dx = F(b) - F(a)$$`)
- Escape dollar signs for currency (e.g., `\$100`)

## Context for Generation

### Topic

The topic is: **{INSERT_TOPIC_HERE}**

Analyze and break it into its most atomic, non-overlapping concepts.

### Atomicity Guidelines

- Each atomic note must contain exactly one core, self-contained idea
- Avoid overlapping or redundant concepts
- Split concepts if they involve distinct cause/effect or problem/solution pairs

### Writing Guidelines

Apply the principles of *On Writing Well* for non-fiction:

- **Clarity**: Use direct, specific language and avoid vagueness
- **Simplicity**: Omit needless words; keep sentences and paragraphs focused
- **Brevity**: Convey ideas in as few words as possible without sacrificing meaning
- **Completeness**: Ensure definitions and explanations cover the essential aspects thoroughly
- **Directness**: Use active voice and straightforward sentence structures
- **Human Touch**: Write in a warm, engaging tone without lapsing into fluff or filler
- **Unity**: Keep each paragraph centered on a single main idea
- **Concrete Details**: Use tangible examples, analogies, or short anecdotes to illustrate key points
- **Good Usage**: Follow standard grammar, punctuation, and spelling; avoid jargon unless truly necessary
