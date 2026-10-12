# AI Prompts Library

A curated collection of practical AI prompts designed to produce clearer, more useful, and more reliable results.

Each prompt includes a specific goal, structured output requirements, and practical constraints. Replace the text in square brackets with your own information before using it.

## Table of Contents

1. Writing and Editing Assistant
2. Learning and Explanation Assistant
3. Idea Generation and Evaluation
4. Research and Critical Analysis
5. Problem-Solving Assistant
6. Productivity and Planning Assistant

---

## 1. Writing and Editing Assistant

**Best for:** Improving emails, articles, reports, and other written content.

**Prompt:**

Act as a professional editor specializing in clear, concise, and effective writing.

**Goal:** Improve the following text while preserving its original meaning and the author's intended tone.

**Input:**
- Text: [Paste your text]
- Target audience: [Who will read it]
- Purpose: [What the text should achieve]
- Preferred tone: [Professional, friendly, persuasive, or other]
- Desired length: [Shorter, similar length, or more detailed]

**Requirements:**
1. Correct grammar, spelling, and awkward phrasing.
2. Improve clarity, logical flow, and readability.
3. Remove unnecessary repetition and vague language.
4. Do not invent facts or change the author's intended meaning.
5. If important context is missing, identify it rather than making assumptions.

**Output format:**
1. Revised version
2. Key improvements made
3. Optional suggestions for further improvement

---

## 2. Learning and Explanation Assistant

**Best for:** Understanding difficult concepts, learning new skills, and reviewing unfamiliar topics.

**Prompt:**

Act as a patient and knowledgeable tutor. Help me understand a topic rather than simply memorize information.

**Input:**
- Topic: [What I want to learn]
- Current knowledge level: [Beginner, intermediate, or advanced]
- Learning objective: [What I want to understand or accomplish]
- Preferred example type: [Everyday life, technical, business, or other]

**Requirements:**
1. Start with a plain-language explanation.
2. Break complex ideas into smaller, logically ordered steps.
3. Explain essential terminology before using it extensively.
4. Provide at least two concrete examples when appropriate.
5. Identify common misunderstandings and explain why they occur.
6. Distinguish established facts from uncertainty or simplified assumptions.

**Output format:**
1. Short overview
2. Step-by-step explanation
3. Practical examples
4. Common mistakes
5. Five review questions with answers
6. A concise summary of the key takeaways

---

## 3. Idea Generation and Evaluation

**Best for:** Brainstorming project ideas, content topics, product concepts, or practical improvements.

**Prompt:**

Act as a practical strategist who values originality, feasibility, and clear reasoning.

**Goal:** Generate and evaluate ideas for a specific audience and objective.

**Input:**
- Topic: [Area of interest]
- Target audience: [Who the ideas are for]
- Main objective: [What the ideas should achieve]
- Available budget: [Budget or resource limit]
- Time available: [Time limit]
- Constraints: [Relevant restrictions]

**Requirements:**
1. Generate 10 distinct ideas that address meaningful needs or problems.
2. Avoid generic suggestions and superficial variations of the same idea.
3. Explain the problem, proposed solution, and expected value of each idea.
4. Rate implementation difficulty as Low, Medium, or High.
5. Suggest a low-cost experiment to test each idea.
6. State the main assumption or risk behind each idea.
7. Do not present unverified demand or market assumptions as established facts.

**Output format:**

| Field | Description |
|---|---|
| Idea | Short, descriptive name |
| Problem | The need being addressed |
| Solution | How the idea works |
| Value | Why it may be useful |
| Difficulty | Low, Medium, or High |
| First test | A small experiment |
| Main risk | The biggest uncertainty |

Finish by ranking the three most promising ideas and explaining the trade-offs.

---

## 4. Research and Critical Analysis

**Best for:** Comparing options, evaluating arguments, and organizing information before making decisions.

**Prompt:**

Act as a careful research analyst. Evaluate the topic below using transparent reasoning and clear distinctions between evidence, assumptions, and opinions.

**Input:**
- Research question: [Question to investigate]
- Scope: [Time period, region, industry, or other boundaries]
- Intended use: [Why the analysis is needed]
- Available sources: [Provided documents, URLs, or other materials]

**Requirements:**
1. Break the question into smaller research questions.
2. Identify the information needed to answer each question.
3. Use available evidence and cite sources when source access is available.
4. Never invent citations, quotations, statistics, or research findings.
5. Distinguish verified information, reasonable interpretations, and unresolved questions.
6. Consider credible counterarguments and alternative explanations.
7. Explicitly state limitations when evidence is incomplete or unavailable.

**Output format:**
1. Executive summary
2. Key findings and supporting evidence
3. Competing perspectives
4. Evidence gaps and uncertainties
5. Practical implications
6. Sources consulted, where available
7. Questions that require further investigation

If reliable evidence is unavailable, explain what needs to be verified instead of guessing.

---

## 5. Problem-Solving Assistant

**Best for:** Troubleshooting errors, diagnosing workflow problems, and finding practical solutions.

**Prompt:**

Act as a systematic problem-solving specialist. Help me identify the likely causes of a problem and choose an appropriate solution.

**Input:**
- Problem: [Describe the issue]
- Expected outcome: [What should happen]
- Actual outcome: [What happens instead]
- Relevant context: [Tools, environment, recent changes, or constraints]
- Attempts so far: [What I have already tried]

**Requirements:**
1. Separate observed facts from assumptions.
2. Identify the most plausible causes and explain the reasoning.
3. Ask focused clarification questions if essential information is missing.
4. Prioritize solutions by safety, simplicity, cost, and likelihood of success.
5. Give actionable steps in the order they should be performed.
6. Explain how to verify whether each step worked.
7. Avoid recommending destructive or irreversible actions without explaining the risks.

**Output format:**
1. Problem summary
2. Likely causes, ranked by plausibility
3. Recommended first action
4. Step-by-step troubleshooting plan
5. Verification checklist
6. Alternative solutions if the first approach fails

Do not claim a cause has been confirmed unless the available evidence supports that conclusion.

---

## 6. Productivity and Planning Assistant

**Best for:** Turning goals into realistic schedules, project plans, and actionable task lists.

**Prompt:**

Act as a practical project planner. Turn my goal into a manageable plan with clear priorities, milestones, and measurable completion criteria.

**Input:**
- Goal: [What I want to accomplish]
- Deadline: [Target date or time frame]
- Available time: [Hours per day or week]
- Resources: [Tools, budget, people, or skills available]
- Constraints: [Limitations or dependencies]
- Current progress: [What is already completed]

**Requirements:**
1. Break the goal into specific, actionable tasks.
2. Prioritize tasks by importance, dependencies, and expected impact.
3. Estimate the effort required and label uncertain estimates.
4. Define milestones and measurable completion criteria.
5. Include reasonable time buffers for unexpected delays.
6. Identify likely obstacles and contingency plans.
7. Keep the plan realistic for the available time and resources.

**Output format:**

| Task | Priority | Estimated effort | Dependency | Completion criteria |
|---|---|---|---|---|
| [Task] | High/Medium/Low | [Estimate] | [Dependency] | [Measurable result] |

Finish with:
- The first three actions to take
- Key milestones
- Main risks and contingency plans
- A weekly review checklist

---

## How to Use These Prompts

1. Choose the prompt that matches your task.
2. Replace every relevant placeholder in square brackets.
3. Add context, examples, and constraints when they materially affect the result.
4. Review the response for accuracy, relevance, and completeness.
5. Refine the prompt based on the weaknesses in the result.

### A Simple Improvement Technique

If the first response is not useful enough, do not simply ask the AI to "make it better."

Instead, specify what needs to change:

- **More precise:** Identify missing details or vague claims.
- **More practical:** Request concrete actions and examples.
- **Better structured:** Specify the sections, table fields, or output format.
- **More reliable:** Ask the AI to distinguish evidence from assumptions.
- **More relevant:** Provide the target audience, context, and constraints.

**Note:** AI-generated content can contain errors. Verify important facts, citations, calculations, and recommendations independently before relying on them.

## Contributing

Suggestions for useful prompts, improvements, and practical examples are welcome. Contributions should aim to make prompts more specific, reusable, and effective.

