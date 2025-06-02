# AI in Action — Day 1

**Duration:** 75 minutes  
**Focus:** Understanding how language models work and experimenting with prompts using Python and DeepSeek.

---

## 🗺️ Objectives

- Introduce core concepts behind large language models (LLMs)
- Experiment with prompt-based interaction using DeepSeek and Python
- Begin setup of the n8n automation tool (used in Day 2)

---

## ⏱️ Timeline

### 00:00 – 00:10 | Introductions
- Who I am
- Who you are:
  - What (if anything) you've used LLMs for
  - What you hope to learn
  - Anything you’re unsure or nervous about

---

### 00:10 – 00:20 | What Is AI? What Are Language Models?
- Overview of artificial intelligence in general
- Focus on **large language models (LLMs)** — tools that generate text
- Examples: ChatGPT, Claude, DeepSeek, etc.

---

### 00:20 – 00:30 | How Language Models Work (Simplified)
- LLMs are trained to predict the next word
  - This simple task can yield behavior that *looks* like understanding
  - That this works is surprising — and powerful
- They are shaped by training data and the *context* you give them
- What matters is the *problem you frame* — the prompt
  - LLMs solve the problem you give them, not necessarily the one you meant
  - The paradox: LLMs are most useful in the hands of people who already know how to think clearly

---

### 00:30 – 00:35 | Transition & Setup
- Form groups of 3–4 students (ideally ≥1 Google account per group)
- Make sure everyone has access to a browser and the DeepSeek chat UI

---

### 00:35 – 00:45 | Hands-On: Chat UI
- Use DeepSeek’s public chat interface
- Try out different kinds of prompts:
  - Tell a story in a specific genre
  - Summarize a topic
  - Rewrite a famous sentence in a new style
- Each group observes:
  - What worked well?
  - What didn’t?
  - What surprised you about the responses?

---

### 00:45 – 01:00 | Hands-On: Sending Prompts with Python
- Students open [this Colab notebook](https://colab.research.google.com/drive/1v6OmWCXhtTaEmOr00h59ejR6K-uxidy4?usp=sharing)
- Instructor walkthrough:
  - Setting up API access to DeepSeek
  - Writing a prompt and reading the response
  - Looping through multiple prompts for comparison
- Notes:
  - You don’t need to know how to code
  - The code is heavily commented and safe to experiment with

---

### 01:00 – 01:15 | Setup for Day 2 (n8n + Task Preview)
- Quick intro to n8n — a no-code automation builder
- Begin account setup or access instructions
- Day 2 task:
  - You’ll take *Moby-Dick*, break it into pieces, and rewrite it in a style of your choice using an LLM
  - Examples: noir, emoji, parody, hyper-formal legalese
  - Goal: create something coherent, stylized, and unexpected

---

## 🧰 Materials

- Browser access
- Google Colab notebook
- DeepSeek API key (provided by instructor)

---

## 🔄 Looking Ahead to Day 2

Tomorrow, you will:
- Use **n8n** to create a simple automated text-rewriting pipeline
- Break a long document (*Moby-Dick*) into chunks
- Feed those chunks into a language model for rewriting
- Compare outputs across different groups and vote on favorites
- Compete for a small prize based on creativity, coherence, or surprise
