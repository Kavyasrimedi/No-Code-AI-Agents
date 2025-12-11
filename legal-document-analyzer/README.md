# Legal Document Analyzer — Agent.ai No-Code Agent

## Overview
A no-code Agent.ai agent that analyzes contracts or contract excerpts and returns a concise, plain-English HTML summary: parties, effective dates, key obligations, risky clauses, deadlines, recommended actions, confidence score, and a disclaimer.

## How to run
1. Open the public Agent.ai link (attach in root README).
2. Upload a text-based PDF, DOCX, or TXT file.
3. Click Run — the agent outputs a structured HTML analysis.

## Inputs
- `legal_file` — uploaded contract text (file input).

## Output
- Structured HTML with sections: Document Summary, Parties, Effective Date / Term, Key Obligations, Top Risky Clauses, Deadlines & Notice Requirements, Recommended Immediate Actions, Confidence, Disclaimer.

## Files in this folder
- `prompt.txt` — exact LLM prompt.
- `workflow.png` — screenshot of Agent.ai workflow (upload from UI).
- `sample-output.html` — example of agent output.
