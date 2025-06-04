# 🧠 Agent Zero - GPT-4o WordPress Chatbot Plugin

Agent Zero is a next-generation WordPress plugin that integrates OpenAI's **GPT-4o** directly into your site through a sleek, customizable chatbot widget. It’s designed for performance, privacy, and plug-and-play ease. Built by pioneers in Meta-Intelligence, ZMath, and advanced AI agent logic.

> “This isn’t just another plugin. It’s part of a recursive intelligence evolution.” – Zero

---

## 🚀 Features

✅ GPT-4o Integration (real-time chat)  
✅ Embed via `[agent_zero_chat]` shortcode  
✅ Clean, modern chat UI (jQuery based)  
✅ Custom agent personality via `agent-data.json`  
✅ Settings panel in WP Admin  
✅ Supports public & private chats  
✅ Pluggable architecture for devs

---

## 🧩 Installation

1. Upload `wp-agent-zero.zip` via **WordPress Admin > Plugins > Add New > Upload Plugin**
2. Activate the plugin from the plugins list
3. Go to **Settings > Agent Zero**
4. Paste your **OpenAI API key**
5. (Optional) Edit `agent-data/default.json` to change system behavior
6. Use the shortcode `[agent_zero_chat]` in any post or page

---

## 📦 Folder Structure

```text
wp-agent-zero/
├── agent-data/
│   └── default.json       <- Agent config/personality file
├── chat.js                <- Chat widget UI (AJAX powered)
├── wp-agent-zero.php      <- Main plugin logic
└── README.md              <- You're here.
