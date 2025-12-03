# **Lesson 07 — Headed vs Headless Mode**

> Module: **05 — Writing Your First Playwright Test**

---

# 🎯 Lesson Objective

Understand:

* Headed vs headless browser modes
* When to use each
* Why automation defaults to headless mode

---

# 📝 Text Mode (Full Explanation)

### **Headless Mode**

Browser UI is hidden.
Runs faster.

```
npx playwright test
```

---

### **Headed Mode**

Shows the browser UI.

```
npx playwright test --headed
```

Useful for debugging.

---

### **Which Should You Use?**

Use **headless** for speed.
Use **headed** for debugging failed tests.

---

# 🧪 Mini Code Challenge

Run a test in both modes:

```
npx playwright test
npx playwright test --headed
```

---

# 📝 Assignment

Write:

**“When I Would Use Headed Mode”**

---

# ❓ Quick Quiz

1. What is headless mode?
2. What is headed mode?
3. Which is faster?
4. Why use headed mode?

---

# 🤖 AI Tutor Prompts

* “Explain headed vs headless like I’m new to automation.”

---

# 💡 Lightbulb Reflection

**Which mode do you prefer so far and why?**

---

# 🎯 Interview Prep

**“Explain headed vs headless browser execution.”**

---