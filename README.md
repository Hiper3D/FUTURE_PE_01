# Future Interns: Task 1 - AI Website Copy Generator 

## Overview
This repository contains the deliverables for Task 1 of the Prompt Engineering Internship. The objective was to design a structured, repeatable prompt system that generates conversion-focused website copy for local businesses, avoiding generic AI language and adapting to specific brand tones.

## Business Profile 
* **Business Name:** Bhubaneswar CityCare Diagnostics
* **Business Type:** Diagnostic Center & Pathology Lab
* **Location:** Bhubaneswar, Odisha

## Prompt Engineering Logic
The master prompt (`master_prompt.txt`) is built as a repeatable "System Template." By isolating variables (`Business Name`, `Target Audience`, `Tone Adaptation`), the prompt can be reused for any local business (e.g., a cafe or salon) simply by changing the variables. 

I applied strict formatting constraints, forcing the LLM to output specific HTML-ready structures (H1/H2 tags, bulleted features, distinct CTA frameworks) rather than a wall of text. I also utilized negative constraints (e.g., "Do not use generic AI filler like 'Welcome to our website'") to ensure the output reads like a premium, human-written wireframe.

## Included Files
1. `master_prompt.txt`: The system instruction set and variable parameters.
2. `website_copy.txt`: The final AI-generated copy, ready for deployment to a web developer or CMS.

## Tools Used
* Generative AI (Google Gemini)
* Generative AI (OpenAI ChatGPT)
* GitHub for version control and documentation
