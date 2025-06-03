# AI in Action — Day 2

**Duration:** 75 minutes  
**Focus:** Building LLM-powered workflows using n8n and rewriting *Moby-Dick* in a custom style.

---

## 🗺️ Objectives

- Set up and explore the n8n visual automation platform
- Understand how to build and extend simple workflows using LLMs
- Modify and iterate on a rewriting pipeline for *Moby-Dick*
- Present group projects and reflect on design choices

---

## ⏱️ Timeline

### 00:00 – 00:10 | Setup and Access
- Distribute n8n invites and confirm that everyone can log in
- Verify access to example workflows and workspace folders
- Short recap of Day 1 materials

---

### 00:10 – 00:25 | Demo: What You Can Build in n8n

#### 1. Chat Interface Demo (simple)
- One input node, one LLM node
- Shows how you can turn a plain text box into a question → response flow

#### 2. Sentiment Analysis Pipeline (intermediate)
- Intakes form (simple review form)
- Uses LLM to classify sentiment with structured outputs
- Results are logged in a connected Google Sheet
- Demonstrates how n8n can connect to APIs *and* external services

#### 3. Chapter Rewriter Template (core)
- A prebuilt workflow that:
  - Downloads Moby Dick
  - Breaks it into chapters
  - Extracts the first chapter
  - Sends it to the LLM with to update style
  - Outputs the result cleanly
- This is the starting point for group work

---

### 00:25 – 01:00 | Group Work: Modify the Rewriting Pipeline
- Students form groups
- Each group starts from the template shown in Demo #3
- Tasks:
  - Decide on a custom style or voice
  - Refine the prompt to guide the LLM effectively
  - (Optional) Add extra features like:
    - Rewriting in multiple steps
    - Tone or summary checks
    - Additional formatting or filtering

---

### 01:00 – 01:15 | Presentations and Voting
Each group will:
- Read aloud the first paragraph or two of their rewritten chapter
- Briefly describe:
  - Style choice
  - How prompts were structured
  - Workflow modifications or enhancements
- Entire class votes on the best team based on:
  1. **Quality-of-life features** added to the pipeline
  2. **Automation flow sophistication**
  3. **Creativity and clarity of the rewritten output** (no rules about what 'good' means for output)

> 🏆 A small prize goes to the team with the most impressive showing

---

## 🧰 Materials

- n8n login credentials (invitations sent during setup)
- Prebuilt workflows:
  - Chat interface (demo only)
  - Sentiment-to-Google Sheets pipeline (demo only)
  - Chapter 1 rewriter template (starting point for groups)

---

## 🧭 Closing Goals

By the end of this session, you should:
- Understand how LLMs can be embedded in real workflows
- Be able to use n8n to create multi-step automation chains
- Be able to prototype your own small AI-powered tool or assistant

