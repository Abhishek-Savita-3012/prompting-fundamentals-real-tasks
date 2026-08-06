# Prompt Iteration Log

## Assignment

**Prompting Fundamentals on Real Tasks v2 (FL-02)**

## Selected Task (From FL-01)

**Target Task 2 – GitHub Documentation**

### Success Criteria

- Professional README
- Installation steps
- Technologies listed
- Markdown formatting
- Easy to understand

## Real Project Used

Retail Sales & Inventory Analytics

---

# Version 0 – Naive Prompt

## Technique

None (Baseline)

## Prompt

> Write a GitHub README for my Retail Sales & Inventory Analytics project.

## Output Excerpt

```md
# 🛍️ Retail Sales & Inventory Analytics

> End-to-end Retail Sales & Inventory Analytics project using **MySQL,
> Python, Pandas, Scikit-learn, Power BI, and Excel**.

## 📌 Project Overview
```

*(Full output available in `outputs/version0-chatgpt.md`)*

## Observation

Although the prompt was intentionally minimal, ChatGPT generated a fairly complete README because it retained context from previous conversations about my project. The output included relevant technologies and project details, but the structure and emphasis still reflected AI assumptions rather than explicit instructions. This highlighted how conversation memory can improve results even when prompt engineering techniques are not used.

## What Changed?

This was the baseline prompt with no prompt engineering techniques applied. I intentionally gave only a one-line instruction to observe how the model would respond without additional guidance.

---

# Version 1 – Role Assignment

## Technique

**Role Assignment**

## Prompt

> You are an experienced GitHub technical writer.
>
> Write a professional GitHub README for my Retail Sales & Inventory Analytics project.

## Output Excerpt

```md
# 🛒 Retail Sales & Inventory Analytics

> A complete end-to-end Retail Analytics project that transforms raw retail data into actionable business insights using **SQL, Python, Power BI, and Excel**.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![SQL](https://img.shields.io/badge/MySQL-Database-orange?logo=mysql)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![License](https://img.shields.io/badge/License-MIT-green)
```

*(Full output available in `outputs/version1-chatgpt.md`)*

## Observation

Assigning ChatGPT the role of an experienced GitHub technical writer immediately improved the professionalism of the README. Compared to the baseline, the headings were better organized, the language was more polished, and the documentation followed common GitHub conventions more closely. However, because I still didn't specify the audience or required sections, the model decided on the content structure itself, which meant some important details were either brief or omitted.

## What Changed?

The only change from Version 0 was assigning the AI a specific role ("experienced GitHub technical writer"). No additional context, formatting instructions, examples, or constraints were provided.

## Why This Improved

Giving the AI a professional role influenced its writing style and organization. Instead of producing a generic response, it adopted a documentation-focused approach, resulting in a README that was clearer and more suitable for a GitHub repository.

---

# Version 2 – Context & Motivation

## Technique

**Context & Motivation**

## Prompt

> You are an experienced GitHub technical writer.
>
> Create a professional GitHub README for my Retail Sales & Inventory Analytics project.
>
> Context:
> This project is part of my Data Analytics portfolio and will be reviewed by recruiters hiring for Data Analyst and Business Intelligence roles.
>
> Goal:
> Write a README that clearly explains the business problem, project objectives, technologies used, key features, business insights, and the value of the project. The content should be professional, easy to understand, and suitable for GitHub.

## Output Excerpt

```md
# 📊 Retail Sales & Inventory Analytics

> End-to-end Retail Sales & Inventory Analytics project using **SQL, Python, Power BI, and Excel** to analyze sales performance, customer behavior, inventory efficiency, and forecast future sales.

![GitHub last commit](https://img.shields.io/github/last-commit/your-username/retail-sales-inventory-analytics)
![GitHub repo size](https://img.shields.io/github/repo-size/your-username/retail-sales-inventory-analytics)
![GitHub stars](https://img.shields.io/github/stars/your-username/retail-sales-inventory-analytics?style=social)
```

*(Full output available in `outputs/version2-chatgpt.md`)*

## Observation

Providing context about the intended audience and the purpose of the README significantly improved the generated content. Instead of focusing only on technical details, the README emphasized the business problem, project objectives, and practical value. The writing became more aligned with what recruiters expect to see in a professional portfolio.

## What Changed?

Compared to Version 1, I added context about who would read the README (recruiters) and why it was being written (to showcase a portfolio project). No formatting examples or structural constraints were introduced.

## Why This Improved

Giving the AI information about the audience and objective helped it prioritize relevant content. The README shifted from being purely descriptive to explaining the project's business impact, making it more suitable for a portfolio intended for job applications.

---

# Version 3 – Few-Shot Examples

## Technique

Few-Shot Examples

## Prompt

> Here is the structure I want:

Example:

# Project Title

## Overview

## Features

## Technologies Used

## Installation

## Dashboard Screenshots

## Business Insights

## Author

Now create a README for my Retail Sales & Inventory Analytics project using the same structure.

## Representative Output

The AI followed the example structure closely and produced a well-organized README with consistent formatting.

## Observation

Providing an example significantly improved consistency and reduced formatting errors.

---

# Version 4 – Output Structure

## Technique

Output Structure

## Prompt

> Create a GitHub README in Markdown.

Include exactly these sections:

1. Project Overview
2. Features
3. Technologies Used
4. Project Architecture
5. Installation
6. Usage
7. Dashboard Preview
8. Business Insights
9. Future Improvements
10. Author

## Representative Output

The README matched the requested section order and used consistent Markdown formatting.

## Observation

Specifying the exact output structure produced a more complete and predictable document with minimal manual reorganization.

---

# Version 5 – Step Decomposition

## Technique

Step Decomposition

## Prompt

> Complete this task in stages.

Step 1:
Understand the Retail Sales & Inventory Analytics project.

Step 2:
Identify the target audience.

Step 3:
Plan the README structure.

Step 4:
Generate the README.

Step 5:
Review the README for completeness, Markdown formatting, clarity, and missing sections.

Step 6:
Suggest improvements before presenting the final version.

## Representative Output

The AI first planned the document, then generated a comprehensive README, reviewed its own work, and suggested improvements before producing the final version.

## Observation

Breaking the task into smaller steps produced the highest-quality README. The generated content required very little editing and closely matched professional GitHub documentation.

---

# Cross-Model Comparison

## Claude

Strengths

- Produced a well-structured README.
- Better explanations for project goals.
- Stronger technical writing style.
- Better organization and Markdown formatting.

Weaknesses

- Sometimes assumed missing project details.
- Required project-specific corrections.

---

## ChatGPT

Strengths

- Produced clear and readable Markdown.
- Included practical installation steps.
- Generated concise explanations.
- Better at following formatting instructions consistently.

Weaknesses

- Occasionally produced shorter business insight sections.
- Needed additional prompting for deeper explanations.

---

## Comparison

Both models produced high-quality documentation when given a detailed prompt.

Claude generated richer explanations and stronger narrative descriptions, while ChatGPT followed formatting instructions more consistently and produced concise, easy-to-read documentation.

The best results came from combining a detailed prompt with manual review regardless of the model used.

---

# Final Reusable Prompt Template

You are an experienced technical documentation writer.

Create a professional GitHub README in Markdown for the following software project.

Project Information:
- Project Name:
- Problem Statement:
- Technologies Used:
- Features:
- Installation Steps:
- Usage Instructions:
- Screenshots:
- Business Insights:
- Future Improvements:

Requirements:

- Write for recruiters and developers.
- Use clear and professional language.
- Organize the README using proper Markdown headings.
- Include installation and usage instructions.
- Explain the project's business value instead of only listing technologies.

Before finishing:

- Review the README for completeness.
- Check Markdown formatting.
- Identify any missing information.
- Suggest possible improvements.

---

# Reflection

This assignment demonstrated how prompt engineering improves AI-generated documentation. Starting with a vague prompt resulted in a generic README that required significant editing. By progressively adding role assignment, context, examples, structured output, and step decomposition, the generated documentation became more professional, organized, and useful.

The biggest improvement came from clearly defining the audience and expected structure. Instead of relying on AI to guess my requirements, I learned that precise prompts produce higher-quality results and reduce manual review time.

This reusable prompt can be applied to future GitHub projects with only project-specific information needing to be updated.
