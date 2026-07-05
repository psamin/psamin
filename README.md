<div align="center">

# hey, i'm praneeth

**incoming Georgia Tech CS + EE student building AI infrastructure**

focused on inference: driving the cost of compute toward zero and making LLMs as scalable as possible.

</div>

---

## 🚀 Featured Projects

### 1. CropAI  
![status](https://img.shields.io/badge/status-finished-blue)
![visibility](https://img.shields.io/badge/visibility-public-blue)

AI crop-monitoring platform: detect plant disease, nutrient, and hydration issues from images, with dashboards for plant health, finances, and farm operations.

**Tech Stack:** React · Flask · Python · TensorFlow · CNNs · LLM Workflows · Tailwind

**Highlights:**
- Reached **86% CNN accuracy** after model tuning
- Combined image classification with an LLM workflow to generate personalized plant health reports
- Placed **2nd Internationally** at TSA Software Development
- Turned down a **$10,000 investment offer**

**Links:**
- 🔗 [Repo](https://github.com/psamin/crop2.0)

<details>
<summary><strong>Key Features</strong></summary>

- Plant disease detection from uploaded images  
- Nutrient deficiency and hydration analysis  
- LLM-generated recommendations  
- Farm health dashboard  
- Financial and operational tracking  
- Saved results and historical tracking  

</details>

---

### 2. JAX Transformer  
![status](https://img.shields.io/badge/status-finished-blue)
![visibility](https://img.shields.io/badge/visibility-public-blue)

A GPT-style language model built from scratch in JAX, implemented after working through *Attention Is All You Need* and DeepMind's scaling laws(Chinchilla). It learns to predict the next character in text. I'm building another one to perform simple arithmetic operations soon.

**Tech Stack:** JAX · optax · NumPy · Python

**Highlights:**
- Implemented multi-head **causal self-attention**, pre-norm residual blocks, and an autoregressive sampler (temperature + top-k) from first principles
- Built the decoder-only architecture: embeddings, attention, feed-forward, residuals, and layer norm
- Fully functional params with a next-token cross-entropy training loop using `jax.jit` / `jax.grad` / `optax`

**Links:**
- 🔗 [Repo](https://github.com/psamin/jax-transformer)

<details>
<summary><strong>What I Built</strong></summary>

- Token + positional embeddings  
- Causal multi-head self-attention (batched, single `einsum`)  
- GELU feed-forward MLP  
- Pre-norm residual transformer blocks  
- Next-token cross-entropy training loop (AdamW via optax)  
- Character-level tokenizer + a small built-in corpus  
- Autoregressive text generation with temperature and top-k  

</details>

---

### 3. Tamil Lens  
![status](https://img.shields.io/badge/status-in_progress-blue)
![visibility](https://img.shields.io/badge/visibility-public-blue)

AI language-learning app: scan real-world objects for Tamil translations, transliterations, audio, flashcards, and quizzes. Piloting with local Tamil schools.

**Tech Stack:** Next.js · React · Flask · Gemini Vision · SQLAlchemy · JWT Auth · Tailwind

**Links:**
- 🔗 [Repo](https://github.com/psamin/tamil-lens2.0)

<details>
<summary><strong>Features</strong></summary>

- Scan real-world objects for vocabulary learning  
- AI-generated translations and transliterations  
- Personal word bank  
- Flashcards and quizzes  
- Streak tracking  
- Stats and achievements  
- Designed for classroom and at-home practice  

</details>

---

### 4. MedBill  
![status](https://img.shields.io/badge/status-in_progress-blue)
![visibility](https://img.shields.io/badge/visibility-public-blue)

AI medical-bill coordination platform for law firms, providers, and funders: extract billing details, compare charges against CMS/Medicare data, and coordinate cases in a shared dashboard.

**Tech Stack:** Next.js · TypeScript · Tailwind · Flask · Python · Claude API · Pydantic · CMS API · Medicare Data · GCP

**Highlights:**
- Built a bill-processing workflow that extracts structured billing data from uploaded medical bill documents
- Integrated CMS/Medicare pricing context to help compare billed charges against public reimbursement data
- Designed role-aware coordination flows for law firms, funders, and providers so each group can review the cases, bills, and details relevant to them
- Created dashboard views for charges, totals, bill status, extracted results, and potential billing issues
- Improved the extraction flow to handle messy bill layouts while keeping token usage efficient
- Deployed the project with cloud infrastructure and a separate frontend/backend setup

**Links:**
- 🔗 [Repo](https://github.com/psamin/medbill)

<details>
<summary><strong>Key Features</strong></summary>

- Medical bill upload and processing  
- Line-item and total charge extraction  
- CMS API / Medicare reference data integration  
- Charge comparison and reimbursement context  
- Shared coordination workflow for law firms, providers, and funders  
- Role-based dashboard organization  
- Structured JSON output from AI parsing  
- Human-readable billing summaries  
- Frontend/backend deployment setup  
- Error handling for inconsistent bill formats  

</details>

---

### 5. Fisker IT Website  
![status](https://img.shields.io/badge/status-finished-blue)
![visibility](https://img.shields.io/badge/visibility-private-gray)

Official website for a local IT company — services, credibility, and client outreach.

**Tech Stack:** React · TypeScript · Tailwind · Flask · Vite

**Impact:** Helped present services to **20+ clients**

**Links:**
- 🌐 [Website](https://fiskeritinc.com)

<details>
<summary><strong>What I Built</strong></summary>

- Responsive landing page  
- Service sections and company overview  
- Modern UI with clean branding  
- Client-facing web presence  
- Backend/contact integration  

</details>

---

### 6. Coding for a Change Website  
![status](https://img.shields.io/badge/status-finished-blue)
![visibility](https://img.shields.io/badge/visibility-private-gray)

Website for my 501(c)(3) nonprofit expanding access to coding education through workshops and student-led programs.

**Tech Stack:** React · Tailwind · JavaScript

**Impact:** Supported my nonprofit’s outreach, workshop visibility, and student-facing coding education programs.

**Links:**
- 🌐 [Website](https://codingforachangenpo.org)

<details>
<summary><strong>What I Built</strong></summary>

- Nonprofit landing page  
- Program and workshop information  
- Student-facing resource sections  
- Clean responsive design  
- Outreach-focused layout  

</details>

---

### 7. Tasks  
![status](https://img.shields.io/badge/status-in_progress-blue)
![visibility](https://img.shields.io/badge/visibility-public-blue)

A lightweight daily planner for mapping out my goals — built around my own workflow.

**Links:**
- 🔗 [Repo](https://github.com/psamin/tasks)

---

### 8. RepoLaunch  
![status](https://img.shields.io/badge/status-in_progress-blue)
![visibility](https://img.shields.io/badge/visibility-public-blue)

Turn unfinished ideas and repos into industry-ready projects — polish, docs, and structure to launch-ready.

**Links:**
- 🔗 [Repo](https://github.com/psamin/RepoLaunch)

---

## 🛠️ Tech Stack

<table>
<tr>
<td valign="top" width="33%">

### 💻 Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-f89820?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-f7df1e?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

</td>
<td valign="top" width="33%">

### 🔧 Frameworks & Tools

![React](https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61dafb)
![Next.js](https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-black?style=for-the-badge&logo=flask&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-38bdf8?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646cff?style=for-the-badge&logo=vite&logoColor=white)
![Git](https://img.shields.io/badge/Git-f05032?style=for-the-badge&logo=git&logoColor=white)

</td>
<td valign="top" width="33%">

### 🤖 AI/ML & Data

![TensorFlow](https://img.shields.io/badge/TensorFlow-ff6f00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-ee4c2c?style=for-the-badge&logo=pytorch&logoColor=white)
![JAX](https://img.shields.io/badge/JAX-4c00b0?style=for-the-badge&logo=google&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-d97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285f4?style=for-the-badge&logo=google&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

</td>
</tr>
</table>

---

## 💬 Let's Connect

<div align="center">

[![Email](https://img.shields.io/badge/Email-praneeths14209%40gmail.com-blue?style=flat&logo=gmail)](mailto:praneeths14209@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Praneeth%20Samineni-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/praneeth-samineni-745902339)

</div>
