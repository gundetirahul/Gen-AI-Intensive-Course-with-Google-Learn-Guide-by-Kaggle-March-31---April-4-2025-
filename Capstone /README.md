
# ✨ LLM Prompt Re-engineer: A Gen AI Capstone Project ✨

This project, developed as part of the **5-day Gen AI Intensive Course with Google and Kaggle**, explores a practical challenge in working with various Large Language Models (LLMs) and presents an intelligent solution using Retrieval Augmented Generation (RAG).

## 🤯 The Problem: Prompting Across Different LLMs

LLMs are powerful, but a prompt that works perfectly for one model might not for another! Different models have unique strengths, training data, and optimal prompting styles (Few-shot, CoT, etc.). Manually tailoring prompts for each LLM is time-consuming trial-and-error.

## 💡 The Solution: A RAG-Powered Assistant

We(AI & I) built an assistant that acts as your personal prompt engineer! It takes your original prompt and intelligently rewrites it for a specific target LLM.

Here's the flow:

1.  🧠 **LLM Knowledge Base:** A curated dataset of 15+ LLMs with their strengths and prompting tips.
2.  🔍 **RAG Retrieval:** Uses embeddings and a vector database (ChromaDB) to quickly find relevant info for the target LLM.
3.  📈 **Prompt Analysis:** An LLM breaks down your original prompt to understand your exact needs.
4.  🔧 **Prompt Re-engineering:** An LLM combines your needs + retrieved LLM tips to craft an optimized prompt.
5.  🤖 **Output Simulation:** (In-notebook) A Gemini model simulates the likely output of the target LLM with the new prompt.

## ✅ Gen AI Capabilities Demonstrated

* Retrieval Augmented Generation (RAG)
* Document Understanding (for prompt analysis)
* Structured Output (for analysis)
* Application of Prompt Engineering Techniques (Few-shot, CoT, APE principles)

## 🚀 Explore the Code & Learn More

Want to see how it works under the hood and experiment yourself?

* **Get the Code:** Find the full, runnable Kaggle Notebook here: **[Gen AI Capstone Project: Cross-Model Prompt Re-engineering Assistant](https://www.kaggle.com/code/rahulgundeti/rahul-genai-capstone/edit)**
* **Read the Story:** Dive deeper into the problem, solution, and development journey in the **[Detailed Blogpost](https://www.linkedin.com/pulse/quest-perfect-prompt-how-we-built-ai-assistant-speak-every-rahul-g-00use/)**

## 🙏 Acknowledgements

Special thanks to Google and Kaggle for the insightful 5-day Gen AI Intensive Course and the opportunity to build this project!

---
