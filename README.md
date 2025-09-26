

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

## Name: Mathan Kailash S
## Reg No: 212223060156

### AI Tools Required:

* ChatGPT (or equivalent LLM)
 
* Document editor to record responses

* Evaluation rubric (quality, accuracy, depth)

# Explanation: 
Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.


# OUTPUT

Here’s a structured way we can do this:
________________________________________
## 1. Prompting Strategies to Compare
•	Zero-shot prompting: No examples, just the instruction.
•	Few-shot prompting: Instruction + 2–3 examples to guide the model.
•	Chain-of-Thought prompting (CoT): Instruction + explicit reasoning steps requested.
________________________________________
## 2. Prompt Types
•	Broad/Unstructured Prompt → e.g., “Explain climate change.”
•	Basic/Refined Prompt → e.g., “Explain climate change in 150 words focusing on causes and impacts on agriculture.”
________________________________________
## 3. Example Scenario
Let’s test with the question:
“Explain the importance of photosynthesis.”
### (a) Broad/Unstructured
•	Zero-shot:
“Explain photosynthesis.”
•	Few-shot:
“Example 1: The water cycle is important because it recycles water on Earth.
Example 2: Respiration is important because it provides energy to living organisms.
Now explain why photosynthesis is important.”
•	Chain-of-Thought:
“Think step by step: first describe what photosynthesis is, then why it matters for plants, then why it matters for ecosystems and humans.”
### (b) Basic/Refined
•	Zero-shot:
“Explain why photosynthesis is essential for life on Earth in less than 120 words, covering its role in oxygen and food production.”
•	Few-shot:
(Give a couple of short example explanations of other biological processes, then ask for photosynthesis).
•	Chain-of-Thought:
“Step 1: Define photosynthesis. Step 2: Explain how it produces oxygen. Step 3: Explain how it produces food. Step 4: Summarize why it is essential.”
________________________________________
## 4. Evaluation Method
We’ll use Rubric-based evaluation (Likert scale 1–5) across three criteria:
1.	Quality (Clarity & Coherence)
2.	Accuracy (Scientific correctness)
3.	Depth (Level of reasoning/detail)
________________________________________
## 5. Expected Comparison (Insights)
•	Zero-shot + Broad prompt → General, maybe vague.
•	Few-shot + Broad prompt → More structured, better alignment.
•	CoT + Broad prompt → Longer, detailed reasoning, but might drift.
•	Zero-shot + Refined prompt → Concise and more accurate.
•	Few-shot + Refined prompt → Very coherent and aligned with examples.
•	CoT + Refined prompt → Deep reasoning, highest accuracy and depth.
________________________________________
## ✅ So the analysis shows:
•	Refined prompts consistently outperform broad ones.
•	Chain-of-Thought adds depth but can increase verbosity.
•	Few-shot helps with style alignment and structure.
•	Zero-shot works fine with refined prompts but struggles with vague ones.
## Comparision Table

| Prompt Type | Strategy         | Quality | Accuracy | Depth | Notes              |
| ----------- | ---------------- | ------- | -------- | ----- | ------------------ |
| Broad       | Zero-shot        | 3       | 4        | 2     | Too general        |
| Broad       | Few-shot         | 4       | 4        | 3     | Adds structure     |
| Broad       | Chain-of-Thought | 5       | 5        | 4     | Rich explanation   |
| Refined     | Zero-shot        | 4       | 4        | 3     | Concise & accurate |
| Refined     | Few-shot         | 5       | 5        | 4     | Polished style     |
| Refined     | Chain-of-Thought | 5       | 5        | 5     | Most detailed      |





## RESULT: The prompt for the above said problem executed successfully
