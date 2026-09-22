# Generative-AI-in-Aviation-Day-3
Day 3 lab exploring prompt engineering, GenAI tool selection, source verification, ChatGPT vs Gemini, hallucination risks, and AI-assisted aviation workflows.  README.md
# ✈️ Generative AI in Aviation — Day 3 Lab

## 📌 Overview

This repository contains my **Day 3 laboratory work on Generative AI Tools for Aviation Management**.

The lab focuses on practical prompt engineering, selecting suitable AI tools for aviation tasks, verifying current aviation information, comparing ChatGPT and Gemini, identifying hallucination risks, and designing an AI-assisted aviation workflow.

---

## 🎯 Learning Objectives

By completing this lab, I learned:

- How to build structured prompts
- The importance of Role, Context, Format and Tone
- How changing one prompt component affects AI output
- How to select the right AI tool for an aviation business task
- Why current aviation information requires source verification
- How to compare ChatGPT and Gemini
- How to identify unsupported AI claims
- How to design a safe AI-assisted aviation workflow
- Why human review is important in aviation
- How Generative AI can support passenger services

---

# 🧩 Practical 1 — Four-Component Prompt Building

The first practical focused on building structured prompts using four important components:

1. **Role**
2. **Context**
3. **Format**
4. **Tone**

### Example

Instead of simply asking:

> Write a flight delay email.

A structured prompt specifies:

- **Role:** Airline passenger-service executive
- **Context:** Flight AV201 delayed by 60 minutes
- **Format:** Email of maximum 120 words with a subject line
- **Tone:** Professional, clear and empathetic

The prompt also specifies information that should **not be invented**, such as:

- Delay reason
- Compensation
- Gate number
- Revised departure time

The structured prompt produced a more controlled and appropriate passenger communication. :contentReference[oaicite:1]{index=1}

---

## 📊 Weak Prompt vs Structured Prompt

| Criteria | Weak Prompt | Structured Prompt |
|---|---|---|
| Role | Not specified | Airline passenger-service executive |
| Context | Very limited | Flight AV201 delayed by 60 minutes |
| Format | Not specified | Email, maximum 120 words |
| Tone | Not specified | Professional, clear and empathetic |
| Invented information | Higher risk | Lower risk |
| Business usefulness | Less consistent | More useful and accurate |

The lab concludes that structured prompts can produce more professional and useful aviation communication while reducing the risk of adding unverified information. :contentReference[oaicite:2]{index=2}

---

# 🎨 Practical 2 — Change One Component

This practical examined how changing only the **tone** of a prompt changes the generated output.

### Version A — Formal & Concise

Focuses on:

- Direct language
- Shorter sentences
- Quick operational information
- Efficiency and clarity

### Version B — Warm & Empathetic

Focuses on:

- Understanding
- Apology
- Reassurance
- Passenger feelings

### Key Learning

Changing only the tone can significantly change how passengers perceive the same information.

A formal tone is useful for operational notices, while a warm and empathetic tone can be useful when passengers are experiencing frustration or inconvenience. :contentReference[oaicite:3]{index=3}

---

# 🛠️ Practical 3 — Aviation Tool Matching

The lab matched aviation business tasks with suitable AI tool categories.

| Aviation Task | Required Output | Tool Category | Human Review |
|---|---|---|---|
| Passenger complaint reply | Email/message | Generative AI – Text | Check facts, tone and promises |
| Current airport information | Verified information | Search/Retrieval AI | Verify official sources |
| Destination campaign visual | Promotional image | Generative AI – Image | Check accuracy, branding and copyright |
| Airport presentation | Slides | Generative AI – Presentation | Check facts and visuals |
| Training voiceover | Script/audio | Generative AI – Voice/Audio | Check pronunciation and accuracy |
| Passenger-feedback summary | Summary | AI Text Analysis/Summarization | Check important feedback |
| Current baggage policy | Latest rules | Search/Retrieval AI | Verify official policy |
| Airline social-media caption | Promotional caption | Generative AI – Text | Check facts and compliance |

### Key Learning

> **The AI tool should be selected according to the business task and required output, not simply by choosing one particular AI tool.**

Current or safety-critical aviation information requires reliable retrieval and human verification, while creative tasks are generally more suitable for Generative AI. :contentReference[oaicite:4]{index=4}

---

# 🔎 Practical 4 — Current Information & Source Check

The lab examined a recent Indian airline digital initiative involving:

- IndiGo
- Digi Yatra Foundation
- Bangalore International Airport Limited (BIAL)
- IATA

The initiative involved technical trials at Kempegowda International Airport Bengaluru for a biometric-enabled, contactless international travel journey.

The lab checked whether the source:

- Opened successfully
- Had an identifiable publisher
- Had a publication/update date
- Discussed the same initiative
- Supported the AI-generated claim
- Was current enough for the question

The source-check exercise demonstrated the importance of verifying AI-generated claims using an identifiable and authoritative source. :contentReference[oaicite:5]{index=5}

---

# 🤖 Practical 5 — ChatGPT vs Gemini

The lab compared ChatGPT and Gemini for aviation passenger-service applications.

### Common Aviation Applications

Generative AI can support:

- Passenger questions
- Check-in information
- Baggage information
- Boarding information
- Airport facilities
- Flight disruptions
- Personalised communication
- Multilingual explanations
- Airport-service recommendations

### Human Review

Human review remains important for:

- Operational disruptions
- Safety-related information
- Security information
- Current flight information
- Baggage rules
- Airport facilities
- Personalised passenger communication

The lab emphasises that Generative AI can improve communication and personalisation, but time-sensitive aviation information should be checked before being communicated. :contentReference[oaicite:6]{index=6}

---

# 📊 ChatGPT vs Gemini — Key Observation

### ChatGPT

- Simple and easy to scan
- Practical passenger-experience applications
- More cautious about unsupported quantitative claims
- Suitable for a first-year student

### Gemini

- More detailed
- More operationally specific
- Includes concepts such as:
  - IROPS
  - AHT
  - LLMs
  - Ancillary revenue
  - Multimodal AI
- Provides detailed ideas such as agent-assist, AI wayfinding and disruption communication

### Important Observation

Neither response should automatically be treated as correct.

Operational details and claimed business impacts should be verified before professional use. :contentReference[oaicite:7]{index=7}

---

# ✈️ Practical 6 — SkyConnect Airlines AI-Assisted Workflow

The final practical developed an AI-assisted customer-service workflow for a fictional airline called **SkyConnect Airlines**.

## Business Problem

Passengers have questions about:

- Check-in
- Flight delays
- Baggage
- Airport navigation
- Booking changes
- Travel preparation

This creates pressure on customer-service staff.

## Users

- Passengers
- SkyConnect customer-service staff

## AI Tool

Generative AI chatbot / AI customer-service assistant

## Inputs

The system may use:

- Passenger question
- Flight number
- Booking details where appropriate
- Verified airline information
- Verified airport information

## Expected Output

A clear and personalised response explaining:

- Relevant procedure
- Current status
- Next steps

## Expected Benefits

- Faster passenger support
- Reduced repetitive workload
- More consistent communication

---

# ⚠️ Possible AI Errors

The AI may:

- Provide outdated flight information
- Misunderstand a passenger's question
- Generate an incorrect baggage response
- Generate an incorrect booking-policy response

Therefore, important information must be verified before action is taken. :contentReference[oaicite:8]{index=8}

---

# 🔐 Information Requiring Verification

The following information should be checked before being communicated:

- Flight status
- Gate
- Boarding time
- Baggage allowance
- Cancellation rules
- Rebooking rules
- Airport facilities
- Safety information
- Security information

---

# 👩‍💼 Human Reviewer

Depending on the issue, the reviewer may be:

- Customer-service agent
- Airport ground staff
- Authorised airline operations employee

---

# 🔄 Final AI-Assisted Aviation Workflow

```text
Passenger Question
        ↓
Verified Aviation Information
        ↓
Generative AI
        ↓
Draft Response
        ↓
Human Verification
        ↓
Approved Information
        ↓
Passenger Communication
        ↓
Operational Action if RequiredKey Learnings
Good prompts produce more controlled outputs.
Role, Context, Format and Tone are important prompt components.
Changing the tone can change how passengers perceive a message.
AI tools should be selected according to the business requirement.
Retrieval is more appropriate for current official aviation information.
Generative AI is useful for creative and communication tasks.
AI-generated information should not automatically be treated as verified.
ChatGPT and Gemini can produce different levels of detail.
Human verification remains important in aviation.
AI should support aviation employees rather than replace accountability.
🛡️ Responsible AI Principles

This lab demonstrates several responsible AI practices:

Human Oversight

Important aviation information should be reviewed by authorised personnel.

Source Verification

Current operational and policy information should be checked against reliable sources.

Controlled Prompting

Prompts should clearly specify what information must not be invented.

Accuracy

AI-generated claims should be checked before professional use.

Appropriate Tool Selection

The AI tool should match the business problem and required output.

Accountability

Human professionals remain responsible for important aviation decisions and actions.

📚 Conclusion

Day 3 helped me understand that using Generative AI effectively is not only about writing a prompt.

Aviation professionals need to:

Identify the business problem

↓

Choose the appropriate AI tool

↓

Build a structured prompt

↓

Generate the required output

↓

Verify important information

↓

Apply human judgement

↓

Take the approved business action

This approach can help aviation organisations use AI more effectively while maintaining accuracy, responsibility and human oversight.

👩‍🎓 Student Details

Name: Harshpreet Kaur
Program: BBA Aviation Management
Lab: Day 3 — GenAI Tools for Aviation Management
University: Chitkara University

🗂️ Repository Structure
Generative-AI-in-Aviation-Day-3/
│
├── README.md
│
├── Lab-3/
│   └── Day-3-Lab-Activity.docx
│
└── Screenshots/
    └── [Lab screenshots]
🔑 Topics Covered

Generative AI
Prompt Engineering
Aviation Management
ChatGPT
Gemini
Tool Selection
Information Retrieval
Source Verification
Hallucination
Human-in-the-Loop
Passenger Service
Airline Operations
Airport Operations
AI Chatbot
Responsible AI
Customer Experience
Aviation Technology


### GitHub fields

| Field | Enter |
|---|---|
| **Repository name** | `Generative-AI-in-Aviation-Day-3` |
| **Description** | `Day 3 lab exploring prompt engineering, GenAI tool selection, source verification, ChatGPT vs Gemini, hallucination risks, and AI-assisted aviation workflows.` |
| **Visibility** | Public |
| **Add README** | ✅ Yes |
| **.gitignore** | None |
| **License** | None |

For your **Day 1, Day 2 and Day 3**, I recommend keeping the naming consistent:

```text
Generative-AI-in-Aviation-Day-1
Generative-AI-in-Aviation-Day-2
Generative-AI-in-Aviation-Day-3

That will make your GitHub portfolio look organized when you add the remaining labs.
