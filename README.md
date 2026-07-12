# 🌍 Context-Anchored Question Answering (RAG Basics)

> **DecodeLabs Prompt Engineering Project 3 (2026)**

A Prompt Engineering project demonstrating **Context-Anchored Answering (RAG Basics)** using a reference document on **Latest Global Geopolitics (July 2026)**. The system answers questions only from the provided document, includes paragraph-level citations, and prevents AI hallucinations through strict negative constraints.

---

# 📌 Project Overview

Large Language Models (LLMs) can sometimes generate incorrect or unsupported information, known as **AI hallucinations**. This project demonstrates how Prompt Engineering techniques reduce hallucinations by restricting the AI model to a specific reference document.

The model behaves as a **Closed-Book Question Answering System**, meaning it answers only from the supplied document. If the requested information is unavailable, it returns **"Information Not Found"** instead of generating unsupported responses.

---

# 🎯 Objectives

* Implement Context-Anchored Answering.
* Understand Retrieval-Augmented Generation (RAG) principles.
* Prevent AI hallucinations.
* Apply strict negative constraints.
* Generate paragraph-level citations.
* Improve factual reliability of AI responses.

---

# 🧠 Key Concepts

* Prompt Engineering
* Context Injection
* Retrieval-Augmented Generation (RAG)
* Closed-Book Question Answering
* AI Hallucination Prevention
* Paragraph-Based Citations

---

# 📂 Repository Structure

```text
Context-Anchored-QA-Using-RAG/
│
├── README.md
├── prompt.txt
├── reference_document.txt
├── sample_questions.txt
├── project_report.pdf
│
└── outputs/
    ├── output1.png
    ├── output2.png
    ├── output3.png
    ├── output4.png
    ├── output5.png
    └── output6.png
```

---

# ⚙️ Project Workflow

```text
Reference Document
        │
        ▼
Context Injection
        │
        ▼
Prompt with Negative Constraints
        │
        ▼
User Question
        │
        ▼
AI Searches Only the Reference Document
        │
        ▼
Answer with Paragraph Citation
        │
        ▼
If Information is Missing
        │
        ▼
Information Not Found
```

---

# 📖 Reference Document

The project uses a custom reference document titled **"Latest Global Geopolitics (July 2026)"** consisting of **11 numbered paragraphs** covering:

* Overview of Geopolitics
* United States–China Relations
* Russia–Ukraine Conflict
* Middle East
* Indo-Pacific Region
* India's Geopolitical Role
* Artificial Intelligence and Technology
* Global Trade and Supply Chains
* Climate and Energy Security
* International Organizations
* Future Outlook

---

# ❓ Sample Questions


1. What are the main areas of strategic competition between the United States and China?

2. Why is the Middle East strategically important in global geopolitics?

3. How do advancements in artificial intelligence and semiconductor manufacturing influence both national security and global economic competitiveness?

4. Explain how India's approach to strategic autonomy aligns with the broader geopolitical trends of economic resilience and international partnerships.

5. Which country currently has the world's largest defense budget in 2026?

6. What is the current President of the United States' official foreign policy toward Taiwan?

---

# 🚫 Hallucination Prevention

This project uses strict prompt constraints to reduce AI hallucinations by enforcing the following rules:

* Answer only from the provided reference document.
* Never use external knowledge.
* Never guess or assume information.
* Return **"Information Not Found"** when the requested information is unavailable.
* Include paragraph-level citations for every supported response.

---

# 💡 Technologies Used

* Prompt Engineering
* Large Language Models (LLMs)
* Retrieval-Augmented Generation (RAG) Principles
* Markdown
* GitHub

---

# 📊 Results

* Successfully implemented Context-Anchored Answering.
* Generated responses using only the reference document.
* Included accurate paragraph citations for supported answers.
* Correctly returned **"Information Not Found"** for unsupported questions.
* Demonstrated effective AI hallucination prevention through prompt constraints.

---

# 🚀 Future Improvements

* Integrate vector databases for semantic retrieval.
* Support multiple reference documents.
* Implement embedding-based document search.
* Build an interactive RAG chatbot.
* Develop a web interface for document-based question answering.

---

# 👨‍💻 Author

**Bodapati Nithin**

**Internship:** DecodeLabs Prompt Engineering Industrial Training (2026)
