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

**Few-Shot Examples**

## Prompt

> You are an experienced GitHub technical writer.
> 
> Create a professional GitHub README for my Retail Sales & Inventory Analytics project.
> 
> Context:
> This project is part of my Data Analytics portfolio and will be reviewed by recruiters hiring for Data Analyst and Business Intelligence roles.
> 
> Here is an example of the style and structure I want:
> 
> # Project Name
> 
> ## Overview
> Briefly explain the project and the problem it solves.
> 
> ## Features
> - Feature 1
> - Feature 2
> - Feature 3
> 
> ## Technologies Used
> - Technology 1
> - Technology 2
> 
> ## Installation
> Step-by-step installation instructions.
> 
> ## Usage
> Explain how to run the project.
> 
> ## Screenshots
> Mention where screenshots can be added.
> 
> ## Author
> Your Name
> 
> Now create a README for my Retail Sales & Inventory Analytics project using a similar style and structure.

## Output Excerpt

```md
# 🛍️ Retail Sales & Inventory Analytics

> An end-to-end Data Analytics project that transforms retail sales and inventory data into actionable business insights using **SQL, Python, Power BI, and Excel**.

![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/retail-sales-inventory-analytics?style=for-the-badge)
![GitHub repo size](https://img.shields.io/github/repo-size/yourusername/retail-sales-inventory-analytics?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)
```

*(Full output available in `outputs/version3-chatgpt.md`)*

## Observation

Providing an example README structure helped the AI closely match the desired formatting and organization. The generated document followed consistent headings, improved section flow, and reduced the amount of manual formatting required. Compared to Version 2, the output was more predictable and visually organized.

## What Changed?

Compared to Version 2, I added a sample README structure for the AI to imitate. The role assignment and project context remained the same, but the AI now had a concrete example to follow.

## Why This Improved

Few-shot prompting reduced ambiguity by showing the AI exactly how I wanted the README to be organized. Instead of deciding the format on its own, it followed the example, producing a more consistent and professional result.

---

---

# Version 4 – Output Structure

## Technique

**Output Structure**

## Prompt

> You are an experienced GitHub technical writer.
> 
> Create a professional GitHub README for my Retail Sales & Inventory Analytics project.
> 
> Context:
> This project is part of my Data Analytics portfolio and will be reviewed by recruiters hiring for Data Analyst and Business Intelligence roles.
> 
> Here is an example of the style and structure I want:
> 
> # Project Name
> 
> ## Overview
> Briefly explain the project and the problem it solves.
> 
> ## Features
> - Feature 1
> - Feature 2
> - Feature 3
> 
> ## Technologies Used
> - Technology 1
> - Technology 2
> 
> ## Installation
> Step-by-step installation instructions.
> 
> ## Usage
> Explain how to run the project.
> 
> ## Screenshots
> Mention where screenshots can be added.
> 
> ## Author
> Your Name
> 
> Use **exactly** the following Markdown structure in your response:
> 
> 1. Project Title
> 2. Project Overview
> 3. Key Features
> 4. Technologies Used
> 5. Project Architecture
> 6. Installation
> 7. Usage
> 8. Dashboard Screenshots
> 9. Business Insights
> 10. Future Improvements
> 11. Author
> 
> Return only the README in Markdown format.

## Output Excerpt

```md
# 📊 Retail Sales & Inventory Analytics

A comprehensive end-to-end **Retail Sales & Inventory Analytics** project that combines **SQL, Python, Power BI, and Excel** to analyze retail business performance, customer behavior, inventory management, and sales forecasting. The project transforms raw retail data into actionable business insights through data cleaning, exploratory analysis, machine learning, and interactive dashboards.

---

# Project Overview

Retail businesses generate large volumes of sales and inventory data every day. Without proper analysis, it becomes difficult to identify high-performing products, understand customer purchasing behavior, optimize inventory levels, and forecast future sales.
```

*(Full output available in `outputs/version4-chatgpt.md`)*

## Observation

Specifying the exact output structure made the generated README much more consistent and predictable. Every required section appeared in the correct order, making the document easier to review and reducing the need for manual reorganization. Compared to Version 3, the output followed the requested format more precisely.

## What Changed?

Compared to Version 3, I explicitly defined the exact Markdown sections and their order. The role assignment, project context, and example structure remained the same, but the AI no longer had to decide how to organize the final document.

## Why This Improved

Providing a fixed output structure reduced ambiguity and ensured that all important information was included. The README became more complete, consistent, and aligned with professional GitHub documentation standards.

---

# Version 5 – Step Decomposition

## Technique

**Step Decomposition**

## Prompt

> You are an experienced GitHub technical writer.
>
> Create a professional GitHub README for my Retail Sales & Inventory Analytics project.
> 
> Context:
> This project is part of my Data Analytics portfolio and will be reviewed by recruiters hiring for Data Analyst and Business Intelligence roles.
>
> Example style:
>
> # Project Name
>
> ## Overview
> 
> ## Features
>
> ## Technologies Used
>
> ## Installation
>
> ## Usage
>
> ## Dashboard Screenshots
>
> ## Business Insights
>
> ## Future Improvements
>
> ## Author
>
> Use exactly this Markdown structure:
>
> 1. Project Title
> 2. Project Overview
> 3. Key Features
> 4. Technologies Used
> 5. Project Architecture
> 6. Installation
> 7. Usage
> 8. Dashboard Screenshots
> 9. Business Insights
> 10. Future Improvements
> 11. Author
>
> Complete the task in these steps:
>
> Step 1: Understand the project and its purpose.
>
> Step 2: Identify the target audience and determine what information they need.
>
> Step 3: Plan the README structure before writing.
>
> Step 4: Generate the complete README.
>
> Step 5: Review the README for completeness, Markdown formatting, clarity, and missing sections.
>
> Step 6: Suggest any improvements and then present the final polished README.
>
> Return only the final improved README in Markdown.

## Output Excerpt

```md
# Retail Sales & Inventory Analytics

## Project Overview

...
```

*(Full output available in `outputs/version5-chatgpt.md`)*

## Observation

Breaking the task into smaller stages produced the most complete and polished README. The AI planned the documentation before writing, reviewed its own output, and generated a final version that required very little manual editing. Compared to Version 4, the README was more comprehensive, consistent, and better aligned with professional GitHub documentation standards.

## What Changed?

Compared to Version 4, I instructed the AI to complete the task in multiple stages: understand the project, identify the audience, plan the structure, generate the README, review it, and suggest improvements before presenting the final version.

## Why This Improved?

Step decomposition encouraged the AI to reason about the task before generating content. This resulted in a more complete README, improved organization, better quality control, and fewer missing sections.

---

# Cross-Model Comparison

The final Version 5 prompt was executed on both ChatGPT and Claude using the same project information.

## ChatGPT

Strengths:
- Generated a detailed and recruiter-friendly README.
- Clearly explained the business problem and project value.
- Followed the requested Markdown structure precisely.
- Included comprehensive feature descriptions, installation steps, and business insights.

Weaknesses:
- Some sections were more detailed than necessary, making the README longer.

---

## Claude

Strengths:
- Produced clean, concise, and professional documentation.
- Installation and usage instructions were easy to follow.
- Maintained consistent Markdown formatting.
- Generated readable technical documentation.

Weaknesses:
- Assumed repository folders (such as `/sql`, `/notebooks`, and `/reports`) that were not explicitly provided.
- Left placeholders for author details and dashboard screenshots instead of completing them.
- Business insights and future improvements were less detailed than ChatGPT's output.

---

## Overall Comparison

Both models generated high-quality GitHub documentation when given the same structured prompt.

ChatGPT produced a more comprehensive README with stronger explanations of business value, making it better suited for a portfolio intended for recruiters.

Claude generated cleaner and more concise technical documentation that would be useful for developers but required minor edits to replace assumed repository paths and placeholders.

The exercise demonstrated that the quality of the prompt had a greater influence on the final output than the choice of AI model. Applying prompt engineering techniques—role assignment, context, few-shot examples, output structure, and step decomposition—significantly improved the documentation produced by both models.

---

# Final Reusable Prompt Template

You are an experienced GitHub technical writer.

Create a professional GitHub README for the following software or data analytics project.

## Project Information

**Project Name:**
<Project Name>

**Project Description:**
<Briefly describe the purpose of the project and the problem it solves.>

**Target Audience:**
<Recruiters, Developers, Hiring Managers, or End Users>

**Technologies Used:**
<List all technologies, programming languages, frameworks, databases, and tools used.>

**Key Features:**
<List the major functionalities or analyses performed in the project.>

**Business Insights or Outcomes:**
<Summarize the most important findings, results, or business value generated by the project.>

**Future Improvements:**
<List possible enhancements or next steps.>

---

### Requirements

Write the README in professional GitHub Markdown format.

Include exactly the following sections:

1. Project Title
2. Project Overview
3. Key Features
4. Technologies Used
5. Project Architecture
6. Installation
7. Usage
8. Screenshots (if applicable)
9. Business Insights
10. Future Improvements
11. Author

Use clear, concise, and professional language suitable for both recruiters and developers.

Before presenting the final README:

1. Verify that every required section is included.
2. Check Markdown formatting and readability.
3. Remove unnecessary repetition.
4. Ensure the README clearly communicates the project's purpose, technical implementation, and business value.

Return only the final README in Markdown format.

---

# Reflection

This assignment demonstrated how prompt engineering significantly improves the quality of AI-generated documentation. Starting with a simple one-line prompt produced a usable README, but it lacked clear direction and relied heavily on the AI's assumptions. By progressively applying prompt engineering techniques—Role Assignment, Context & Motivation, Few-Shot Examples, Output Structure, and Step Decomposition—the generated documentation became more structured, relevant, and professional.

The most noticeable improvement came from providing context about the intended audience and explicitly defining the required output structure. These additions helped the AI focus on explaining the project's business value rather than simply listing technical details. Step decomposition further improved the quality by encouraging the AI to plan, review, and refine its response before presenting the final output.

Comparing ChatGPT and Claude also showed that prompt quality had a greater impact than the choice of model. ChatGPT generated a more detailed, recruiter-focused README, while Claude produced concise and well-organized technical documentation. Both models produced strong results when provided with clear instructions.

Overall, this exercise reinforced that effective AI usage is not about asking a single question—it is about designing prompts that clearly communicate the task, audience, constraints, and expected output. This approach reduces manual editing, improves consistency, and produces documentation that is ready for professional use.
