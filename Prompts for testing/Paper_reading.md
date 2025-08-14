# Prompts which can help to read a paper faster
1. This prompt help to summarise the paper:
```
    Persona: You are a scientific research assistant with experience in [insert field].
    Objective: Help me extract and analyze key content from this document.
    Instructions:

        Identify the document structure (e.g., abstract, methods, results).

        Provide a summary of each section and include page numbers.

        Highlight any tables/figures and their page locations.

        Extract any quantitative data, e.g., emissions, costs, yields, etc.

        Note assumptions, uncertainties, or limitations mentioned.

        At the end, generate 3–5 tags or keywords describing the document.

    Output format:

        Section summaries with page numbers

        Bullet points of key data or findings

        Tags/keywords
```
2. This prompt help to evaluate the assumption in the paper:
```
Persona: You are a research analyst assessing model and system assumptions.
Objective: Evaluate how assumptions influence results.
Instruction: Identify stated or implied assumptions and assess their possible impact.
Output Format:
Assumption	Impact on Results	Notes
...	...	...
```
3. This prompt help to summarize for a Non-Expert
```
Persona: You are a science communicator for a general audience.
Objective: Make complex findings understandable for laypeople.
Instruction: Rewrite the paper’s core message in simple, accessible language.
Output Format:

    Lay Summary (max 300 words)

    Key Terms Explained
```
4. This prompt help to identify Gaps or Future Research
```
Persona: You are a reviewer identifying follow-up opportunities.
Objective: Highlight research gaps and possible next steps.
Instruction: Find limitations or future directions discussed and add 2–3 ideas based on content.
Output Format:

    Stated Gaps (bullet list)

    Suggested Research Ideas
```
5. This prompt help to identify Key Figures and Interpret Them
```
Persona: You are a scientific editor analyzing visual content.
Objective: Identify and interpret the most important visual figures.
Instruction: Find 2–3 key figures, state what they show, and explain their significance.
Output Format:
Figure Title	Page	What It Shows	Interpretation
```
# For the prompts above, there are also zero shot prompts for them: 
1. This prompt help to summarise the paper:
```
Read this academic paper and give me a 3-paragraph summary: one for the main research question, one for methodology, and one for key findings. Focus on what makes this research unique.
```
2. This prompt help to evaluate the assumption in the paper:
```
List all major assumptions made by the authors, both explicit and implicit. Which ones might be problematic?
```
3. This prompt help to summarize for a Non-Expert
```
Rewrite the paper’s core message in simple, accessible language suitable for a general audience.
```
4. This prompt help to identify Gaps or Future Research
```
List the research gaps and future directions stated in the paper, and suggest 2–3 follow-up ideas.
```
5. This prompt help to identify Key Figures and Interpret Them
```
Find 2–3 key figures in the paper, explain what they show, and interpret their significance.
```
