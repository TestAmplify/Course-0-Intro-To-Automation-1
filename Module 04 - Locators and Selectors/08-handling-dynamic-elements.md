# **Lesson 08 — Handling Dynamic Elements**

> Module: **04 — Locators and Selectors**

---

# 🎯 Lesson Objective

Understand:

* Why dynamic elements are difficult
* How Playwright handles dynamic UI
* Strategies for stable automation

---

# 📝 Text Mode (Full Explanation)

Dynamic elements:

* Appear late
* Disappear fast
* Change position
* Change text
* Animate in/out

Playwright automatically waits for:

✔ Visibility
✔ Stable state
✔ Attachment to DOM
✔ No animation

But stable locators are still required.

---

### **Strategies**

* Use `getByRole`
* Use stable attributes
* Avoid timing hacks
* Prefer `await locator.click()` over manual waits

---

# 🧪 Mini Code Challenge

Find a dynamic element on a page.
Describe what makes it dynamic.

---

# 📝 Assignment

Write:

**“How I Will Handle Dynamic Elements in Automation”**

---

# ❓ Quick Quiz

1. What causes dynamic DOM behavior?
2. What makes automation fail on dynamic pages?
3. How does Playwright help?

---

# 🤖 AI Tutor Prompts

* “Explain how to test dynamic UI components.”

---

# 💡 Lightbulb Reflection

**Which dynamic behavior surprised you the most?**

---

# 🎯 Interview Prep

**“How do you handle dynamic elements in Playwright?”**

---