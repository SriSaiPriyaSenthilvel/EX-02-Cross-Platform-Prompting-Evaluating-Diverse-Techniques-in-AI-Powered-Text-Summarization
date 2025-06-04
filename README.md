# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm

Article Selection Select a ~500-word technical article titled "The Basics of Blockchain Technology".

Prompting Strategies Definition Prepare the following four prompting strategies:

Zero-shot: Directly ask the model to summarize without examples.
Few-shot: Provide 2–3 examples of summaries for similar technical texts before asking for the summary.
Chain-of-Thought: Prompt the model to explain or break down the text logically before summarizing.
Role-based: Instruct the model to act as a specific role (e.g., “a university professor summarizing for freshmen”).
Platform Selection Use the following AI platforms:

ChatGPT (OpenAI)
Gemini (Google)
Claude (Anthropic)
Copilot (Microsoft)
Execution For each platform:

Apply each prompting strategy using the same input article.
Record the output summary.
Note time taken to generate the summary.
Evaluation Criteria Evaluate each generated summary using the following:

Accuracy: Does the summary correctly capture the main points of the article?
Coherence: Is the summary logically structured and easy to follow?
Simplicity: Is the language accessible for undergraduate students?
Speed: How fast is the response?
User Experience: Was the interface intuitive, and was the output easy to copy/save?
Scoring & Analysis

Assign scores (1 to 5) for each criterion across all combinations.
Tabulate results for comparison.
Identify the best-performing strategy-platform combination

## Result

![image](https://github.com/user-attachments/assets/85fa8101-69ea-4014-b269-43eb3d8f683f)


Best Performing Combination: Claude + Role-based Prompting and ChatGPT + Few-shot Prompting both scored 24/25, showing high effectiveness in summarizing complex content in a simple and structured way for undergraduates.
