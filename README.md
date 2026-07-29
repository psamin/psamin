<div align="center">

# hey, i'm praneeth

**incoming Georgia Tech CS + EE**

currently focused on inference, ML systems, and hardware-software co-design.

</div>

---

## 🚀 Featured Projects

### Transformers
![status](https://img.shields.io/badge/status-in_progress-blue)
![visibility](https://img.shields.io/badge/visibility-public-blue)

A collection of GPT-style transformer implementations and experiments in PyTorch and JAX.

The PyTorch model references [Andrej Karpathy's tutorial](https://www.youtube.com/watch?v=kCc8FmEb1nY&t=1463s) and generates Shakespearean text. The JAX model is trained on OpenWebText and was built after working through *Attention Is All You Need* and DeepMind's Scaling Book.

**Tech Stack:** PyTorch · JAX · Flax NNX · Optax · Orbax · XLA · Python

**Highlights:**
- Implemented causal self-attention, multi-head attention, residual blocks, layer normalization, and autoregressive generation
- Built next-token prediction training loops in both PyTorch and JAX
- Used `jax.jit`, automatic differentiation, Optax, and XLA for accelerated training
- Continuing to add new transformer architectures and experiments

**Links:**
- 🔗 [Repo](https://github.com/psamin/transformers)

<details>
<summary><strong>What I Built</strong></summary>

- PyTorch GPT-style model trained to generate Shakespearean text
- JAX GPT-style model trained on OpenWebText
- Token and positional embeddings
- Causal multi-head self-attention
- Feed-forward neural networks
- Pre-norm residual transformer blocks
- Next-token cross-entropy training
- Autoregressive generation with temperature and top-k sampling
- Checkpointing and accelerated training with Orbax and XLA

</details>

---

### CropAI
![status](https://img.shields.io/badge/status-finished-blue)
![visibility](https://img.shields.io/badge/visibility-public-blue)

AI crop-monitoring platform that detects plant disease, nutrient deficiencies, and hydration issues from images, then generates personalized plant-health reports.

**Tech Stack:** React · Flask · Python · TensorFlow · CNNs · LLM Workflows · Tailwind

**Highlights:**
- Reached **86% CNN accuracy** after model tuning
- Combined image classification with an LLM workflow to generate personalized recommendations
- Placed **2nd internationally** at TSA Software Development
- Turned down a **$10,000 investment offer**

**Links:**
- 🔗 [Repo](https://github.com/psamin/crop2.0)

<details>
<summary><strong>Key Features</strong></summary>

- Plant disease detection from uploaded images
- Nutrient deficiency and hydration analysis
- LLM-generated health recommendations
- Farm health and operations dashboard
- Financial tracking
- Saved results and historical analysis

</details>

---

### MedBill
![status](https://img.shields.io/badge/status-in_progress-blue)
![visibility](https://img.shields.io/badge/visibility-public-blue)

AI medical-bill coordination platform for law firms, healthcare providers, and funders.

**Tech Stack:** Next.js · TypeScript · Flask · Python · Claude API · Pydantic · CMS API · Medicare Data · GCP

**Highlights:**
- Extracts structured line items and billing data from uploaded medical documents
- Compares charges against CMS and Medicare reimbursement data
- Supports role-based workflows for law firms, providers, and funders
- Handles inconsistent document layouts while keeping token usage efficient
- Deployed with separate cloud-hosted frontend and backend services

**Links:**
- 🔗 [Repo](https://github.com/psamin/medbill)

<details>
<summary><strong>Key Features</strong></summary>

- Medical-bill upload and processing
- Line-item and total-charge extraction
- CMS and Medicare reference-data integration
- Role-based dashboards and permissions
- Structured JSON output from AI parsing
- Human-readable billing summaries
- Error handling for inconsistent bill formats
- Cloud deployment setup

</details>

---

### Tamil Lens
![status](https://img.shields.io/badge/status-in_progress-blue)
![visibility](https://img.shields.io/badge/visibility-public-blue)

AI language-learning platform that lets students scan real-world objects for Tamil translations, transliterations, audio, flashcards, and quizzes.

**Tech Stack:** Next.js · React · Flask · Gemini Vision · SQLAlchemy · JWT Auth · Tailwind

**Highlights:**
- Piloted with a local Tamil school serving **1,000+ students**
- Uses computer vision to turn real-world objects into vocabulary lessons
- Supports classroom and at-home language practice

**Links:**
- 🔗 [Repo](https://github.com/psamin/tamil-lens2.0)

<details>
<summary><strong>Key Features</strong></summary>

- Object scanning for vocabulary learning
- AI-generated translations and transliterations
- Personal word bank
- Flashcards and quizzes
- Streak tracking
- Statistics and achievements
- Classroom and at-home practice

</details>

---

### Fisker IT Website
![status](https://img.shields.io/badge/status-finished-blue)
![visibility](https://img.shields.io/badge/visibility-private-gray)

Official website for a local IT company, designed to present its services, credibility, and client work.

**Tech Stack:** React · TypeScript · Tailwind · Flask · Vite

**Impact:** Helped present services to **20+ clients**

**Links:**
- 🌐 [Website](https://fiskeritinc.com)

<details>
<summary><strong>What I Built</strong></summary>

- Responsive landing page
- Service and company-overview sections
- Modern branded interface
- Client-facing web presence
- Backend contact integration

</details>

---

### Coding for a Change Website
![status](https://img.shields.io/badge/status-finished-blue)
![visibility](https://img.shields.io/badge/visibility-private-gray)

Website for my 501(c)(3) nonprofit expanding access to coding education through workshops and student-led programs.

**Tech Stack:** React · Tailwind · JavaScript

**Impact:** Supported coding programs serving **250+ students** and contributing **2,600+ volunteer hours**

**Links:**
- 🌐 [Website](https://codingforachangenpo.org)

<details>
<summary><strong>What I Built</strong></summary>

- Nonprofit landing page
- Program and workshop information
- Student-facing resources
- Responsive interface
- Outreach-focused design

</details>

---

### Tasks
![status](https://img.shields.io/badge/status-in_progress-blue)
![visibility](https://img.shields.io/badge/visibility-public-blue)

A lightweight daily planner built around my personal workflow for organizing tasks and goals.

**Links:**
- 🔗 [Repo](https://github.com/psamin/tasks)

---

### RepoLaunch
![status](https://img.shields.io/badge/status-in_progress-blue)
![visibility](https://img.shields.io/badge/visibility-public-blue)

A platform for turning unfinished repositories into polished, documented, and launch-ready projects.

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

![PyTorch](https://img.shields.io/badge/PyTorch-ee4c2c?style=for-the-badge&logo=pytorch&logoColor=white)
![JAX](https://img.shields.io/badge/JAX-4c00b0?style=for-the-badge&logo=google&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-ff6f00?style=for-the-badge&logo=tensorflow&logoColor=white)
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
```
