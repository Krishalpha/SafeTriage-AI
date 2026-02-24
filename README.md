# 🩺 SafeTriage
Hybrid AI Clinical Escalation with Deterministic Safety Guardrails

SafeTriage is an offline medical triage assistant that combines LLM reasoning (MedGemma) with deterministic clinical safety rules to prevent missed high-risk cases.

---

## 🚨 Problem

Large language models are powerful but unsafe alone in medical triage.  
Missing high-risk cases (false negatives) can lead to severe consequences.

---

## 🧠 Solution

SafeTriage integrates:

- MedGemma-4B-Instruct for structured triage reasoning
- Deterministic safety override layer
- JSON output enforcement
- False-negative monitoring
- Stress testing framework
- Gradio-based interactive demo

---

## 🛡 Safety Performance

- 100% accuracy on structured evaluation cases
- 0 False Negatives (No high-risk case missed)
- Conservative escalation bias (1 false positive)

---

## 🎥 Demo Video

Watch the full demo here:
https://youtu.be/mGc1HZrZOoc

---

## ⚙️ Architecture

LLM Reasoning → JSON Parsing → Deterministic Safety Rules → Final Escalation Output

---

## 💡 Designed For

Community health workers operating in low-resource or offline settings.

---

SafeTriage demonstrates how combining probabilistic AI with deterministic guardrails creates safer real-world clinical AI systems.
