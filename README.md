# AI Masterclass 2025

## Welcome

Welcome to the AI Masterclass 2025!

By the end of this course, you will gain hands-on practical knowledge in:

- Building and deploying applications with Llama Stack
- Implementing Retrieval Augmented Generation (RAG) systems
- Evaluating AI model performance and implementing safeguards
- Best practices for responsible AI development

This masterclass combines presentations with (lots of) hands-on exercises to ensure you walk away with real skills.

## When and where

- Mon, May 12 to Wed, May 14
- Trinity College, Dublin

## Schedule

- [Mon, May 12] Unit 1 - Introduction to Llama Stack
- [Tue, May 13] Unit 2 - Building RAG Applications with Docling
- [Wed, May 14] Unit 3 - Evaluating and Safeguarding AI Applications

## Instructors

- [Mac Misiura](https://github.com/m-misiura)
- [Michele Dolfi](https://github.com/dolfim-ibm)
- [Diego Maniloff](https://github.com/dmaniloff)

## To compile the slides contained in this branch

1. Terminal 1:

```bash
 export $(cat examples/.env | xargs) && llama stack run examples/remote_vllm.yaml
```

2. Terminal 2: 

```
quarto preview presentation.qmd--no-browser --no-watch-inputs
```