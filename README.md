# 🧪 Periodic Table of Process Improvement Tools | 改善ツールの周期表

A bilingual, interactive web app that helps project teams and problem-solvers explore over 100 Lean and Six Sigma tools — organized like a periodic table. Designed to make process improvement more accessible, practical, and actionable.

## 🧠 What This Project Does

This tool makes it easy for users to:
- Browse over 100 process improvement tools visually, categorized by function
- Filter tools by **Lean**, **Six Sigma**, or **DMAIC phase**
- Click on any tile to get:
  - A plain-language explanation of the tool
  - Real-world usage examples
  - A suggested starting Action Plan

Users can also type in a challenge, and AI will recommend suitable tools based on natural-language input — in both **English** and **Japanese**.

## 🎯 Why It Matters

When we face a quality or process challenge, knowing that tools exist isn’t enough. We often get stuck deciding **which tool to use**, **how to use it**, or **how to start** — especially for those new to continuous improvement.

I personally faced this during my Green Belt (C-IMP) project at Air Liquide Japan. I realized many of us knew about SIPOC, Fishbone, FMEA — but felt unsure when applying them in real scenarios.

So I spent several weeks gathering data, organizing tools, and building this reference table — not just as a list, but as an experience that makes learning interactive and useful for actual field application.

> 💡 The design was inspired by Balaji L R’s periodic quality tool post on LinkedIn — and also by the fact that at Air Liquide, we work daily with elements, molecules, and gases. This table bridges technical inspiration and human usability.

## 🚀 Features

- 🧪 **Periodic Table Layout** — Each tile represents a tool, color-coded by category
- 🔍 **Search & Filter Options** — By tool type, DMAIC phase, or Lean/Six Sigma label
- 🧠 **Gemini AI Integration** — Suggests tools based on problem description
- 📋 **Action Plan Generator** — Shows how to get started with any selected tool
- 🌐 **Bilingual Interface** — Toggle between Japanese and English
- 📱 Fully mobile-friendly layout

## 🔎 Example Use Cases

- “I’m having trouble identifying process waste” → Suggests TIMWOODS, VSM, etc.  
- “Customer complaints are rising” → Recommends VOC tools, Pareto, and Root Cause tools  
- “I’m in the Measure phase of DMAIC” → Filters tools for that stage  

## 🛠️ Tech Stack / Tools Used

- HTML, Tailwind CSS, Vanilla JavaScript  
- Gemini API for tool explanations and recommendations  
- Fully client-side logic with dynamic rendering  
- Bilingual translation toggle  
- Responsive grid layout

## 🌐 Live Demo

👉 [https://khanhaissam.github.io/process-tools-periodic-table/](https://khanhaissam.github.io/process-tools-periodic-table/)

## 🧪 How to Run This Project

> No setup needed — just clone and open `index.html` in your browser.


### 🧭 Step 1: Use the Tool
1. Hover over a tool to preview its purpose
2. Click to open the full detail panel
3. Or type your problem into the search bar for suggestions
4. Toggle language with the top-right language switch


### 🔑 Step 2: Add Gemini API Key (Optional, for AI features)

To enable AI-based tool suggestions and explanations:

1. Sign up at [https://makersuite.google.com/](https://makersuite.google.com/)
2. In your HTML script section, find the Gemini fetch request and replace this line:

```js
const apiUrl = "https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-pro:generateContent?key=YOUR_GEMINI_API_KEY";


