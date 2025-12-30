![build the future](https://img.shields.io/badge/build%20the%20future-google%20ai-blue)
![gemini](https://img.shields.io/badge/gemini-powered-brightgreen)
![google ai studio](https://img.shields.io/badge/google%20ai%20studio-used-orange)
![ai for good](https://img.shields.io/badge/ai%20for%20good-healthcare-red)
![status](https://img.shields.io/badge/status-live%20prototype-success)

# 🚑 MedSync AI  
### AI-Powered Emergency Triage & Hospital Routing with Gemini

**MedSync AI** is an AI-assisted emergency coordination system that helps emergency teams triage patients, assess risk, and route them to the most prepared hospital in real time — reducing delays, preventing ER overload, and improving life-critical decision making.

Built using **Google AI Studio + Gemini** as part of the **Startup School: Prompt to Prototype** program and submitted to the **Build the Future Showcase**.

---

## Why MedSync AI Exists

Emergency departments operate under extreme pressure. Critical patients often wait too long, ambulances are sent to overloaded hospitals, and staff are forced to make complex decisions with incomplete information.

MedSync AI was created to answer a simple but urgent question:

> *What if emergency responders could see patient risk and hospital readiness at the same time?*

---

## What It Does

MedSync AI provides **AI-assisted decision support** for emergency response by:

- Assigning triage levels based on patient vitals and symptoms  
- Estimating risk of deterioration  
- Recommending the best hospital based on capacity, specialists, and travel time  
- Triggering time-critical alerts for cardiac, stroke, and trauma cases  
- Producing clear, explainable outputs for human review  

The system is designed to support clinicians — not replace them.

---

## How It Works

MedSync AI is powered by a **structured system instruction (“Golden Prompt”)** built in **Google AI Studio**.

Gemini acts as a **virtual emergency coordinator**, reasoning across:
- Patient condition  
- Hospital readiness  
- Time sensitivity  
- Safety constraints  

All logic is encoded through **prompt engineering**, making the model itself the core decision engine.

---

## System Architecture

```text
[User / Paramedic]
        │
        ▼
[AI Studio Web App / Swift UI]
        │
        ▼
[Golden Prompt (System Instruction)]
        │
        ▼
[Gemini Reasoning Engine]
        │
        ▼
[Triage + Risk + Routing Decision]
        │
        ▼
[Explainable JSON Output]
        │
        ▼
[Human Review & Action]
