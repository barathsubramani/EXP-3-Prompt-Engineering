# EXP-3 — Prompt Engineering

## Aim
The aim of this experiment is to evaluate and compare the **2024 prompting tools** across diverse AI platforms such as **ChatGPT, Claude, Bard, Cohere Command, and Meta Experiment**.  

Using a specific use case — **text summarization** and **technical question answering** — the study focuses on:
- **Response Quality**: correctness, coherence, completeness, and factual reliability.  
- **User Experience**: ease of use, clarity of platform interface, latency, and flexibility in prompting.  
- **Platform Behavior**: adaptability to prompt variations, adherence to instructions, and handling of constraints (like word limits).  

The objective is to identify the **strengths, limitations, and practical applications** of each AI platform when used for prompt engineering.

---

## Algorithm

The experiment workflow follows the **Prompt → Output → Result** pattern:

### 1. Prompt
- Design uniform prompts for two use cases:  
  **a) Summarization:**  
  *“Summarize the following passage in 3–4 sentences, focusing only on the main idea and two supporting details. Do not add extra information.”*  

  **b) Technical Question Answering:**  
  *“Explain the difference between Breadth-First Search (BFS) and Depth-First Search (DFS) with a simple Python example.”*  

- Ensure the same prompt is submitted across all platforms for fairness.

### 2. Output
- Each platform (ChatGPT, Claude, Bard, Cohere Command, Meta Experiment) generates a response.  
- Responses are recorded along with metadata such as:  
  - Time taken to generate output  
  - Token usage (if visible)  
  - Style of writing (concise, verbose, detailed)  
  - Any deviation from the prompt  

### 3. Result
- Responses are evaluated based on:  
  - **Accuracy & Faithfulness** (facts correct? summary faithful?)  
  - **Completeness & Relevance** (coverage of required details)  
  - **Clarity & Fluency** (natural and easy to understand)  
  - **Conciseness** (matches requested length)  
  - **User Experience** (ease of use, speed, cost-effectiveness)  

- A comparative analysis is drawn to rank or categorize each tool’s performance.

---

## Observation
- **ChatGPT**: Produced highly coherent and fluent responses. Strong at following instructions (e.g., word limits) and excellent for structured outputs like code.  
- **Claude**: Strong at maintaining factual correctness and ethical safeguards. Sometimes verbose, but good at nuanced summaries.  
- **Bard (Google)**: Quick responses, wide knowledge coverage. Occasionally less precise, but strong in creative summarization.  
- **Cohere Command**: Good for technical summarization and concise outputs, though less natural fluency compared to ChatGPT or Claude.  
- **Meta Experiment**: Balanced results, efficient in short-form summaries, but occasionally weaker in complex reasoning tasks.  

---

## Inference
- **For Summarization:** ChatGPT and Claude produced the most faithful and coherent summaries. Bard was good but sometimes added extra details. Cohere was concise but less fluent. Meta Experiment was efficient but less reliable for longer passages.  
- **For Technical QA:** ChatGPT excelled in generating runnable Python code and clear explanations. Claude provided strong conceptual clarity. Bard was average but sometimes creative. Cohere was short and direct. Meta Experiment handled basics well but struggled with depth.  

---

## Conclusion
This experiment demonstrates that **prompt engineering outcomes vary across platforms**, even with the same input prompts.  

- **ChatGPT**: Best for technical accuracy, code generation, and structured outputs.  
- **Claude**: Best for nuanced explanations and ethical alignment.  
- **Bard**: Good for fast, creative summarization but less consistent in precision.  
- **Cohere Command**: Best for concise responses, suitable for short prompts.  
- **Meta Experiment**: Balanced but less specialized, suitable for general tasks.  

👉 The choice of **AI platform depends on the intended application**:  
- For **technical Q&A and programming help**, ChatGPT is optimal.  
- For **balanced summarization and safe outputs**, Claude is preferable.  
- For **speed and creativity**, Bard is effective.  
- For **lightweight summarization**, Cohere and Meta Experiment perform adequately.  
