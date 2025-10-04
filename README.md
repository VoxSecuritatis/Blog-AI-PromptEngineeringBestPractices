# Blog:  Prompt Engineering Best Practices and Examples

Published: 2025-02-21 | Last Update: 2025-10-04

---

## Introduction
Prompt engineering is both an art and a science—it's about crafting effective instructions to get the best possible outputs from AI models like ChatGPT and other large language models (LLMs). Clear and well-structured prompts ensure high-quality responses, making this a vital skill for anyone working with AI. This guide covers best practices in prompt engineering, complete with practical examples to help you fully leverage AI models.

---

## 1. Be Clear and Specific
### Why It Matters
Vague prompts often yield equally vague responses. By being precise, you guide the AI toward accurate and relevant answers.

### Tips
- Use straightforward language.
- Specify the desired length, format, or level of detail.

### Example
- **Poor Prompt:** "Tell me about climate change."  
- **Better Prompt:** "Explain the causes and effects of climate change in under 150 words."

> **Insight:** Specificity helps the AI focus on what matters, reducing the risk of broad or generic answers.

---

## 2. Provide Context and Constraints
### Why It Matters
Context guides the AI, while constraints (like tone or word count) refine the response.

### Tips
- Mention the target audience.
- Set clear parameters for tone, style, and length.

### Example
"Explain machine learning to a high school student using simple language and everyday examples, in 100 words or less."

> **Insight:** Context ensures the AI tailors its response to your intended audience or use case.

---

## 3. Use Role-Based Prompts
### Why It Matters
Assigning a role helps the AI adopt a specific perspective or expertise.

### Tips
- Use roles like "cybersecurity analyst," "career coach," or "nutritionist."
- Ensure the role aligns with your desired output.

### Examples
- "You are a cybersecurity analyst. Explain how to prevent phishing attacks."  
- "Act as a career coach. Provide resume tips for data analyst applicants."

> **Insight:** Role-based prompts improve both the relevance and authority of AI-generated responses.

---

## 4. Break Down Complex Requests
### Why It Matters
Complex queries can confuse the AI. Breaking them into smaller steps ensures clearer, more comprehensive responses.

### Tips
- Split multi-step tasks into sequential prompts.
- Request layered responses (e.g., explain first, then provide examples).

### Example
"First, explain what a neural network is. Then, describe its role in image recognition."

> **Insight:** Step-by-step instructions yield structured, easy-to-follow answers.

---

## 5. Use Examples and Counterexamples
### Why It Matters
Examples show the AI what you want, reducing guesswork.

### Tips
- Include examples of both good and bad outputs.
- Use them to clarify formatting, tone, or detail preferences.

### Example
"List healthy snacks (e.g., almonds, carrots) and avoid processed options."

> **Insight:** Clear examples lead to more accurate and aligned responses.

---

## 6. Iterative Refinement
### Why It Matters
You might not get the perfect response on the first try. Iterating helps fine-tune the output.

### Tips
- Start with a basic prompt, then refine based on the AI’s response.
- Use follow-ups like "Can you elaborate?" or "Rewrite with technical terms."

> **Insight:** Think of prompt engineering as a dialogue rather than a one-off command.

---

## 7. Use Templates for Repetitive Tasks
### Why It Matters
Templates ensure consistency and save time, especially for recurring requests.

### Tips
- Create reusable formats for reports, summaries, or analyses.
- Add placeholders for variable information.

### Example
"Summarize the article with:  
1. Main Idea  
2. Key Points  
3. Conclusion"

> **Insight:** Templates streamline your workflow while maintaining quality.

---

## 8. Experiment with Prompt Length
### Why It Matters
Prompt length affects both the focus and depth of the AI’s response.

### Tips
- Use shorter prompts for quick facts.
- Use longer prompts for detailed explanations with context.

> **Insight:** Finding the right balance improves both clarity and content richness.

---

## 9. Use Few-Shot Learning Techniques
### Why It Matters
Providing examples within the prompt helps the AI recognize patterns or formats.

### Tips
- Include one or two examples before making your request.
- Use few-shot learning to guide complex outputs.

### Example
"Translate into French:  
- 'Good morning.' → 'Bonjour.'  
Now translate: 'How are you?'"

> **Insight:** Few-shot examples help the AI understand your expectations more effectively.

---

## Quick Tip
Refining prompts through feedback loops is essential for AI/ML projects. Start general, assess the response, and tweak your instructions for better results.

---

## Prompt Template
Use this template to apply the best practices covered in this guide:

**[Role Assignment (optional)]:** You are a [role, e.g., cybersecurity analyst, career coach, data scientist].

**[Task Description]:** [Clearly describe what you want the AI to do. Be specific and unambiguous.]

**[Context (optional)]:** [Provide background information or details to guide the AI’s response.]

**[Constraints]:**  
- Word count: [e.g., 150 words]  
- Tone/Style: [e.g., professional, conversational, technical]  
- Format: [e.g., bullet points, paragraph, numbered list]  

**[Examples (optional)]:**  
- Desired output: [Good example of the response you’re looking for.]  
- Undesired output: [Example of what to avoid.]  

**[Follow-Up Request (optional)]:** [Ask for elaboration or adjustments if needed.]```

## Example Using the Template

**Role Assignment:** You are a marketing strategist.

**Task Description:** Provide five creative social media campaign ideas for a new eco-friendly water bottle brand.

**Context:** The target audience is environmentally conscious millennials who value sustainability and style.

**Constraints:**  
- Word count: 100 words per idea  
- Tone/Style: Creative and engaging  
- Format: Bullet points  

**Examples:**  
- Desired output: "Host a challenge where users share their outdoor adventures with the water bottle."  
- Undesired output: "Just advertise the product."  

**Follow-Up Request:** Expand on the most innovative idea with recommended platforms and hashtags.

> **Tip:** Use this template to create prompts that are structured, clear, and optimized for the best AI responses.

## Blank Template 
> Copy and paste the Template into Notepad, fill out sections, then copy and paste into LLM prompt.

Role Assignment: 

Task Description:  

Context:

Constraints: 
- Word count:   
- Tone/Style: 
- Format:  

Examples: 
- Desired output:   
- Undesired output:  

Follow-Up Request: 

---

## Final Thoughts
Mastering prompt engineering unlocks the full potential of AI models. By being clear, providing context, assigning roles, breaking down tasks, and iterating, you’ll generate more accurate and relevant outputs.

---

© 2025 Brock Frary. All rights reserved.
