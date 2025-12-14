# 🔍 Competitive Insight Extractor (LLM/Gemini)

## Project Overview
This project demonstrates the use of **Multimodal LLMs (Gemini 2.5 Flash)** and **Python** to automate competitive analysis. It processes any public YouTube video URL and generates a highly constrained, structured strategic brief for executive leadership.

**Goal:** To convert long-form competitor video content into **actionable intelligence** on market positioning, quantified data, and strategic vulnerabilities, minimizing research time.

## 🎯 Strategic Output Example
*(Showcases the final, professional output structure)*

---
### **Sample Competitor Strategic Analysis Brief**

1.  **Core Positioning & Message (USP):** The primary message centers on 'simplifying complex data workflows' for mid-market businesses, emphasizing integration speed and low learning curve as their core differentiators.
2.  **Quantified Data & Metrics:**
    * They report a **25% faster** deployment time compared to the market average.
    * Customer churn has fallen to **under 4%** in the past quarter.
    * Targeting **$5M ARR** by Q3 2026.
3.  **Identified Weaknesses & Market Gaps:**
    * The platform lacks dedicated mobile support for deep analytics.
    * Compliance with specific EU data residency laws was not mentioned, suggesting a vulnerability.
    * Pricing structure is unclear for high-volume enterprise clients.
4.  **Urgent Strategic Recommendation:** Immediately launch a campaign highlighting our comprehensive mobile support and clear, transparent enterprise pricing tiers.
---

## 🛠️ Technology Stack & Execution

| Component | Role | Status |
| :--- | :--- | :--- |
| **LLM Model** | Gemini 2.5 Flash | Multimodal analysis of video content (audio/visual). |
| **Metadata** | `pytube` Library | Retrieves Title, Channel, and Duration for reporting. |
| **Key Skill** | Advanced Prompt Engineering | Ensures structured output (positioning, data, weaknesses). |
