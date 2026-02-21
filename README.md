---

# 🧠 Cortex BRD — Business Requirements Intelligence

Cortex BRD is an AI-powered Business Requirements Document (BRD) generation platform designed to transform unstructured business communication (emails, meetings, chats, documents) into structured, audit-ready BRDs.

Built for **HackFest 2.0**, this system demonstrates intelligent requirement extraction, stakeholder mapping, risk analysis, and traceability — all inside a modern web dashboard.

---

## 🚀 Features

### 📊 Dashboard

* Real-time project statistics
* Total BRDs generated
* Requirements extracted
* High-risk flags identified
* Recent activity tracking

### 🏗 Project Management

* Create and manage multiple projects
* Industry tagging (FinTech, Healthcare, SaaS, etc.)
* Status tracking (Active / Archived)
* LocalStorage-based persistence

### ⚡ AI-Powered BRD Generation

* Multi-channel input ingestion:

  * Emails
  * Meeting notes
  * Chat logs
  * Documents
  * Tickets
* Intelligent requirement extraction
* Stakeholder identification
* Risk detection & classification
* Timeline creation
* Knowledge graph mapping
* Versioned BRD storage

### 📄 Structured BRD Output Includes

* Executive Summary
* Functional Requirements
* Non-Functional Requirements
* Stakeholders
* Risks & Mitigation Plans
* Timeline
* Scope (In/Out)
* Traceability mapping

---

## 🧩 How It Works

1. **Ingest**
   Paste raw business communication into the input panel.

2. **Extract**
   NLP pipeline filters noise and extracts:

   * Requirements
   * Decisions
   * Stakeholders
   * Budget references
   * Timelines

3. **Map**
   Builds structured models:

   * Knowledge graph
   * Stakeholder influence scoring
   * Requirement lifecycle tracking

4. **Generate**
   Produces an audit-ready BRD document with structured tabs:

   * Document
   * Requirements
   * Stakeholders
   * Risks
   * Timeline
   * Knowledge Graph

---

## 🛠 Tech Stack

### Frontend

* HTML5
* CSS3 (Custom design system)
* Vanilla JavaScript
* LocalStorage for in-memory DB

### Backend (Optional)

* Node.js
* SQLite (for persistent storage)
* Run:

  ```bash
  node backend/server.js
  ```

If backend is not running, system works in **in-memory mode** using browser storage.

---

## 🗂 Project Structure

```
/project-root
│
├── index.html          # Main application UI
├── backend/
│   └── server.js       # Optional Node + SQLite backend
├── README.md
```

---

## 📦 Installation & Usage

### 1️⃣ Clone the Repository

```bash
git clone <your-repo-url>
cd cortex-brd
```

### 2️⃣ Run Frontend

Simply open:

```
index.html
```

in your browser.

### 3️⃣ (Optional) Enable Backend Persistence

```bash
cd backend
npm install
node server.js
```

---

## 📈 Data Model

The system maintains:

* `projects`
* `brds`
* `activity logs`

Each BRD contains:

* Version number
* Requirements array
* Risks array
* Stakeholders array
* Timeline events
* Knowledge graph structure

---

## 🎯 Use Cases

* Business Analysts
* Product Managers
* Startup Founders
* Consulting Teams
* Enterprise Transformation Projects
* Hackathon Demonstrations

---

## 🔐 Current Limitations

* AI simulation logic (can be replaced with real LLM API)
* LocalStorage limit for large datasets
* No authentication layer
* Backend optional (default: in-memory)

---

## 🌟 Future Enhancements

* Real LLM API integration (Claude / OpenAI)
* PDF export
* Requirement traceability matrix export
* Role-based access control
* Multi-user collaboration
* Cloud deployment

---

## 🏆 HackFest 2.0 Submission

Project Name: **Cortex BRD**
Version: **v1.0**
Tagline: *Business Requirements Intelligence Engine*

---

## 👨‍💻 Author

Built for HackFest 2.0
Team: [Your Team Name]

---
