# Prompt Engineering Assignment — Submission

**Student:** (Your Name)  
**Date:** 2025-10-08

---

## 1) Tools and Prompts Used

### Task 1 — Prompt Chaining for a Customer Support AI
**Tools:** Python 3, Google Colab (optional), simple `call_ai()` mock function (no API needed).  
**Key Prompts (examples used in the notebook):**
- "STEP 1: Customer Support greeting & info request"
- "STEP 2: Summarize issue + policies"
- "STEP 3: Offer resolution options"
- "STEP 4: Confirm choice + wrap up"

### Task 2 — Code Generation with ReACT Prompting
**Tools:** Python 3, Google Colab (optional), simple `call_ai()` mock function.  
**Key Prompt:**
- "Use ReACT style and write Python code inside a code block."  
  (The mock returns a Thought → Action (code) → Observation, then the notebook extracts the code and runs it.)

### Task 3 — Self-Reflection Prompt for Improving Output
**Tools:** Python 3, Google Colab (optional), simple `call_ai()` mock function.  
**Key Prompts:**
- "Write a concise summary (1 sentence) of this short article: ..."
- "Critique the summary (1-2 sentences). Summary: "<summary>""
- "Improve the summary (1 sentence). Previous summary: "<summary>" Critique: "<critique>""

---

## 2) GitHub Links to Colab Notebooks (with successful output)

> Upload the three `.ipynb` files in this folder to your GitHub repo, then paste the links below.
> Tip: Colab link format is usually: `https://colab.research.google.com/github/USERNAME/REPO/blob/BRANCH/PATH_TO_FILE.ipynb`

- **Task 1 (Prompt Chaining)**  
  GitHub: <https://github.com/YOUR_USERNAME/YOUR_REPO/blob/main/task1_prompt_chaining_customer_support.ipynb>  
  Open in Colab: <https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/task1_prompt_chaining_customer_support.ipynb>

- **Task 2 (ReACT Code Generation)**  
  GitHub: <https://github.com/YOUR_USERNAME/YOUR_REPO/blob/main/task2_react_code_generation.ipynb>  
  Open in Colab: <https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/task2_react_code_generation.ipynb>

- **Task 3 (Self-Reflection Prompt)**  
  GitHub: <https://github.com/YOUR_USERNAME/YOUR_REPO/blob/main/task3_self_reflection_prompt.ipynb>  
  Open in Colab: <https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/task3_self_reflection_prompt.ipynb>

---

## How I Verified "Successful Output"
- **Task 1:** The notebook prints the four-step support dialog with the user's simulated replies.
- **Task 2:** The notebook prints the ReACT response, extracts the Fibonacci Python code, runs it, and prints a list of 10 numbers.
- **Task 3:** The notebook prints an initial summary, a critique, and an improved one-sentence summary.