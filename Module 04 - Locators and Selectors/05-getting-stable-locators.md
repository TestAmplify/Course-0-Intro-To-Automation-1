# **Lesson 05 — Getting Stable Locators**

> Module: **04 — Locators and Selectors**

---

# 🎯 Lesson Objective

Learn:

* What makes a locator stable
* What attributes are reliable
* What attributes to avoid
* Why stability prevents flaky tests

---

# 📝 Text Mode (Full Explanation)

### **Good Locators Use Stable Attributes**

Use:

✔ `id`
✔ `data-testid`
✔ Stable text
✔ Unique roles
✔ Semantic structure

---

### **Unstable Locators**

Avoid:

❌ Dynamic IDs
❌ Auto-generated classes
❌ Styling classes
❌ Position-based selectors

These cause flakiness.

---

### **Examples**

Good:

```
button[data-testid="submit"]
```

Bad:

```
button:nth-child(3)
```

---

# 🧪 Mini Code Challenge

Find 2 stable attributes on real websites.

---

# 📝 Assignment

Write:

**“Three Stable Locators I Found Online”**

---

# ❓ Quick Quiz

1. What makes a locator stable?
2. What attributes should be avoided?
3. Provide an example of a stable locator.

---

# 🤖 AI Tutor Prompts

* “Explain stable vs unstable locators.”

---

# 💡 Lightbulb Reflection

**What type of locator do you think is most stable?**

---

# 🎯 Interview Prep

**“How do you choose stable selectors?”**

---