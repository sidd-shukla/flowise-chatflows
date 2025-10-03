# Flowise Chatflows

This repository contains exported **Flowise** chatflow JSON files. These exports capture the structure of AI chatbots and agents I have built using [Flowise Cloud](https://cloud.flowiseai.com).

By importing these JSON files into Flowise, you can replicate the exact flows (nodes, prompts, chains, agents) and customize them for your own projects.

---

## 🚀 How to Import a Chatflow into Flowise

### Option 1: Import into Flowise Cloud
1. Log in to your [Flowise Cloud](https://cloud.flowiseai.com) account.
2. From the left sidebar, go to **Chatflows**.
3. Click **+ New Chatflow** → then choose **Import Chatflow** (you’ll see an option to upload a JSON file).
4. Upload one of the `.json` files from this repository (e.g. `hello-flowise-v1.json`).
5. Once imported, the flow will appear in your chatflows list. You can edit and run it immediately.

### Option 2: Import into Local / Self-hosted Flowise
1. Run Flowise locally (or via Docker) → open the UI at `http://localhost:3000`.
2. Go to **Chatflows** in the sidebar.
3. Click **Import** (top-right).
4. Select a `.json` file from this repo.
5. The chatflow will appear in your workspace.

---

## 📂 Repository Structure

flowise-chatflows/
│
├── hello-flowise-v1.json # Simple chatbot with ChatOpenAI + Prompt + LLM Chain
├── polite-concierge-v2.json # Version with improved prompt style
└── (future exports here)

---

## ✨ Tips
- You need a valid **OpenAI API key** (or other model provider key) set up in Flowise under **Credentials**.
- After importing, always check the **LLM node settings** and reselect your credential, since API keys are not exported for security reasons.
- You can duplicate flows in Flowise to create new versions and export them back here for version control.

---

## 📜 License
Feel free to fork and modify. Please credit the original repo if you share improved versions.

