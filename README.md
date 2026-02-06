Understanding Engineering Design Patents with LLMs: An Exploratory Study
This repository contains the supplementary materials for the paper "Can Large Language Models Understand Engineering Design Patents? An Exploratory Study", submitted to DESIGN 2026 (19th International Design Conference).

Project Overview
As Large Language Models (LLMs) become embedded in innovation processes, it is critical to understand their capacity for interpreting design intent rather than just legal text. This exploratory study assesses the capabilities of GPT-5 and Gemini 2.5 Pro in analysing three key design aspects:
Motivation: Problems addressed by the invention.
Novelty: Core novel concepts or claims.
Key Invention Features: Core components and their interrelationships.

Repository Contents
To comply with conference page limits while maintaining scientific transparency, the following resources are provided:
1. LLM Prompt Specification
The full system prompt and JSON schema used to guide the LLMs. This includes:
2. Patent Corpus
The three US patents selected for this pilot study, representing a spectrum of mechanical and mechatronic complexity :
US11647866: Grinder/Doser device for coffee beans.
US10631685: Toaster.
US8529203: Fan assembly (Bladeless Fan).
3. Example LLM outputs

Reproducibility
To replicate the results:
Attach the provided patent PDFs.
Input the text into the LLM (GPT-5 or Gemini 2.5 Pro) along with the Prompt Specification.
Compare the resulting JSON output against the provided Expert Rating Table (found in the manuscript).

Limitations
This is an exploratory study based on a limited sample of three patents and two experts. The findings represent early evidence of LLM performance patterns and failure modes.

Citation
If you use these prompts or rubrics in your research, please cite our DESIGN 2026 paper:

Full citation to be updated following conference publication.
