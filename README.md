# FUTURE_PE_01
AI Website Copy Generator.
# Future Interns: Task 1 - AI Website Copy Generator 

## Overview
This repository contains the deliverables for Task 1 of the Prompt Engineering Internship. The objective was to design a structured, repeatable prompt system that generates conversion-focused website copy for local businesses, avoiding generic AI language.

## Business Profile 
* **Business Name:** Bhubaneswar CityCare Diagnostics
* **Business Type:** Diagnostic Center & Path Lab
* **Location:** Bhubaneswar, Odisha

## Prompt Engineering Logic
Instead of asking the AI to "write a website," I designed a variable-based master prompt (`master_prompt.txt`). By defining explicit variables for `[Business Name]`, `[Location]`, `[Target Audience]`, and `[Tone]`, this prompt acts as a scalable template. It forces the LLM to output structured data specifically tailored for a web builder (Homepage, Services, and CTAs) rather than a block of unstructured text. 

## Included Files
1. `master_prompt.txt`: The variable-based instruction set.
2. `website_copy.txt`: The generated output, ready for deployment.

## Tools Used
* Generative AI (Google Gemini)
* Generative AI (OpenAI ChatGPT)
* GitHub for version control and documentation
