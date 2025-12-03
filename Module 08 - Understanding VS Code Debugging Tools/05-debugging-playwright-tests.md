# **Lesson 05 — Debugging Playwright Tests**

> Module: **08 — Understanding VS Code Debugging Tools**

---

# 🎯 Lesson Objective

You will learn:

* How to debug Playwright tests specifically
* How to use PWDEBUG mode
* How to pause tests dynamically
* How to inspect locators visually

---

# 📝 Text Mode (Full Explanation)

### **PWDEBUG Mode**

Run:

```
PWDEBUG=1 npx playwright test
```

This opens:

* Inspector window
* DOM snapshots
* Step controls
* Visual timeline

---

### **Playwright `page.pause()`**

You can pause inside a test:

```
await page.pause();
```

This opens the Playwright Inspector instantly.

---

### **What You Can Do in Inspector**

✔ See live DOM
✔ Highlight locators
✔ Click elements
✔ Test selectors
✔ Step through script

---

# 🧪 Mini Code Challenge

Add:

```
await page.pause();
```

Run the test and explore the Inspector.

---

# 📝 Assignment

Write:

**“How PWDEBUG Helped Me Debug a Locator”**

---

# ❓ Quick Quiz

1. What does PWDEBUG do?
2. What does `page.pause()` do?
3. What can you inspect in the Inspector?

---

# 🤖 AI Tutor Prompts

* “Explain how to use Playwright Inspector effectively.”

---

# 💡 Lightbulb Reflection

**What was the most useful feature of the Inspector?**

---

# 🎯 Interview Prep

**“How do you debug a Playwright test?”**

---