# 🧠 AI Agent Chat Workflow - n8n

This repository contains an **n8n workflow** that implements a smart chat-based AI agent using OpenAI, memory, and tool integrations.

## 🛠️ Workflow Overview

This workflow listens for a **chat message** and passes it to an **AI Agent** which uses:

- 🤖 `OpenAI Chat Model` (`gpt-4o-mini`)
- 🧠 `Simple Memory` node
- 🧮 `Calculator` tool
- 🔍 `SerpAPI` for web search queries

The agent is capable of answering questions, performing calculations, and retrieving real-time information from the web.

## 📂 Workflow Nodes

| Node                   | Purpose                            |
|------------------------|------------------------------------|
| When chat message received | Trigger when a new message is received |
| AI Agent               | The core intelligent agent         |
| OpenAI Chat Model      | Language processing (LLM)          |
| Simple Memory          | Retains conversation context       |
| Calculator             | Handles basic calculations         |
| SerpAPI                | Searches the web for answers       |

## 🚀 Getting Started

1. **Clone this repo** or download the workflow file.
2. **Import workflow** into your n8n instance (Cloud or Self-Hosted).
3. **Set credentials** for:
   - `OpenAI API`
   - `SerpAPI`
4. Activate the workflow (once credentials are set).

## 🔐 Required Credentials

- OpenAI API key (for the Chat Model)
- SerpAPI key (for web search)

## 📸 Screenshot

![Workflow Screenshot](https://github.com/user-attachments/assets/40db326a-c53e-4ead-b077-b3ae63d8550b)

