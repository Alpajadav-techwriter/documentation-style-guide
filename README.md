# ✏️ Documentation Style Guide

> Writing standards, tone guidelines, terminology, and formatting rules
> for consistent, high-quality technical documentation.

---

## 📋 Overview

This style guide defines the standards for all technical documentation
produced by the Information Development team. All writers are expected
to follow these guidelines to ensure consistency across all deliverables.

---

## 1. Writing Principles

### 1.1 User-Centered Writing
- Write for the **user's goal**, not the product's feature
- Answer the question: *"What is the user trying to accomplish?"*
- Use **task-based headings** — "Creating a User Account" not "User Account Feature"

### 1.2 Clarity
- Use **plain language** — write at a Grade 8 reading level for general audiences
- Use **short sentences** — aim for 15–20 words maximum per sentence
- Use **active voice** — "Click Save" not "The Save button should be clicked"
- Define technical terms on first use

### 1.3 Conciseness
- Remove filler words — "simply", "just", "basically", "very"
- Remove redundant phrases — "click on" → "click", "in order to" → "to"
- Keep paragraphs to 3–5 sentences maximum

---

## 2. Tone and Voice

| Use | Avoid |
|---|---|
| Professional and friendly | Casual or overly formal |
| Second person — "you" | Third person — "the user" |
| Present tense | Future tense where possible |
| Active voice | Passive voice |
| Positive framing | Negative framing |

**Examples:**

✅ **Good:** "Click Save to create your account."
❌ **Avoid:** "The account will be created when the Save button is clicked by the user."

✅ **Good:** "Enter a valid email address."
❌ **Avoid:** "Do not enter an invalid email address."

---

## 3. Formatting Standards

### 3.1 Headings
- Use **sentence case** — "Getting started with the API" not "Getting Started With The API"
- Keep headings **concise** — under 8 words where possible
- Use heading levels logically — do not skip levels (H1 → H3)

### 3.2 Lists
- Use **bulleted lists** for unordered items (3 or more)
- Use **numbered lists** for sequential steps
- Keep list items **parallel in structure**
- Do not use more than **2 levels** of nesting

### 3.3 Code and UI Elements

| Element | Formatting |
|---|---|
| Code, commands, file names | `code font` |
| UI elements (buttons, menus) | **Bold** |
| Field names | **Bold** |
| Variables and placeholders | *Italic* or `<placeholder>` |
| Keyboard shortcuts | **Ctrl+S** |

### 3.4 Notes and Warnings

> 📝 **Note:** Use for supplementary information that helps users.

> ⚠️ **Important:** Use for information that prevents errors.

> 🚫 **Warning:** Use for information that prevents data loss or serious issues.

---

## 4. Terminology Guide

### 4.1 Preferred Terms

| Use | Avoid |
|---|---|
| click | click on, press, hit |
| select | choose, pick |
| enter | type, input, key in |
| navigate to | go to, access |
| displays | shows, appears |
| ensure | make sure |
| requires | needs |

### 4.2 Capitalization
- Product names: always capitalize — **Employee Management System**
- UI elements: capitalize as they appear in the UI
- Feature names: capitalize — **Advanced Search**, **Export Report**
- General terms: lowercase — user account, dashboard, settings

---

## 5. API Documentation Standards

### 5.1 Endpoint Descriptions
- Start with an **action verb** — "Retrieves", "Creates", "Updates", "Deletes"
- Keep to **1-2 sentences**
- Describe **what**, not **how**

### 5.2 Parameter Descriptions
- State whether **required or optional** clearly
- Include **data type** and **valid values/ranges**
- Give a **concrete example** where helpful

### 5.3 Code Samples
- Provide examples in at least **2 languages** — cURL + Python or JavaScript
- Use **realistic, meaningful** values — not "string" or "value123"
- Include **comments** in code samples to explain key steps

---

## 6. Review Checklist

Before submitting documentation for review, verify:

- [ ] Follows active voice throughout
- [ ] Uses second person ("you")
- [ ] No filler words or redundant phrases
- [ ] All UI elements formatted correctly
- [ ] All code formatted in code blocks
- [ ] Steps are numbered and sequential
- [ ] Notes and warnings used appropriately
- [ ] Terminology consistent with this guide
- [ ] Reviewed with AI style check tool (Copilot/ChatGPT)
- [ ] Reviewed by SME for technical accuracy
