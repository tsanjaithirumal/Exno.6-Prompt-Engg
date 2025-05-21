# 📘 Experiment No. 6 – Prompt Engineering

**📅 Date:**  
**🆔 Register No.:**  

---

## 🎯 Aim

To develop a comprehensive Python program capable of interacting with multiple AI tools through APIs (such as OpenAI, Hugging Face, Google PaLM, etc.) to automate prompt-based queries. The goal is to compare the responses across platforms and generate insights based on response quality, contextual accuracy, and usefulness.

---

## 📚 Concepts Covered

- Prompt Engineering
- Python Programming
- API Integration (REST APIs)
- JSON Data Handling
- NLP Response Evaluation
- Comparative Metrics
- Insight Generation

---

## 📋 Algorithm

### Step 1: Setup the Environment
- Install Python libraries: `requests`, `json`, `dotenv` (for environment variables).
- Store and load API keys securely using environment variables.

### Step 2: Define Prompt and AI Tool Endpoints
- Create a common input prompt for testing.
- Store API URLs and configurations for each AI tool.

### Step 3: Implement API Functions
- Create Python functions to interact with:
  - OpenAI
  - Hugging Face
  - Google PaLM (or other tools)
- Send the same prompt to all platforms.

### Step 4: Collect Responses
- Retrieve responses from each AI model.
- Parse the results into a standardized structure.

### Step 5: Analyze and Compare Outputs
- Evaluate the outputs based on:
  - Clarity
  - Relevance
  - Creativity/Depth
- Use string similarity metrics (optional: cosine similarity).

### Step 6: Generate Comparative Report
- Summarize results in tabular or bullet form.
- Indicate which model performed best in specific metrics.

### Step 7: Output and Logging
- Display the best response.
- Save comparison results to a file (optional: JSON/CSV).

---

## 💡 Sample Prompt Used

```text
Prompt: "Explain the impact of artificial intelligence in modern healthcare."
=== AI Comparison Report ===

Prompt:
"Explain the impact of artificial intelligence in modern healthcare."

OpenAI:
"AI assists in diagnostics, drug discovery, and personalized treatment, reducing human error and speeding up processes."

Hugging Face:
"AI is used to analyze medical data, predict patient risks, and assist doctors in surgeries and diagnosis."

Google PaLM:
"Artificial intelligence is revolutionizing healthcare with robotic surgeries, digital patient records, and clinical decision support systems."

--- Comparison Summary ---
🔹 Most Concise Response: Hugging Face  
🔹 Most Detailed Response: Google PaLM  
🔹 Best Contextual Fit: OpenAI  
🔹 Suggested Tool for Healthcare Insights: OpenAI
```
## **Result:**
The corresponding prompt is executed successfully ✅
