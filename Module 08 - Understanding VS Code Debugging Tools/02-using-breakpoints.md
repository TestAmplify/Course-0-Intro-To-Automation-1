# **Lesson 02 — Using Breakpoints**

> Module: **08 — Understanding VS Code Debugging Tools**

---

# 🎯 Lesson Objective

You will learn:

* What breakpoints are
* How to set breakpoints
* How breakpoints pause test execution
* Why breakpoints are useful for analyzing automation behavior

---

# 📝 Text Mode (Full Explanation)

### **What Is a Breakpoint?**

A breakpoint tells VS Code:

> “Stop the program at this exact line.”

This lets you:

* Inspect variables
* Inspect locators
* Observe the DOM
* Check page state
* Move through the test step-by-step

---

### **How to Add a Breakpoint**

1. Open a test file
2. Click next to the line number
3. A red dot appears → this marks the breakpoint

---

### **Running with Breakpoints**

Open the **Run and Debug** panel:

* Select **JavaScript Debug Terminal** or **Playwright Debug**
* Run your test
* Execution will pause at your breakpoint

---

# 🧪 Mini Code Challenge

Set a breakpoint at:

```
await page.goto('https://example.com');
```

Run the test and confirm the browser stops.

---

# 📝 Assignment

Write:

**“Where I Set My First Breakpoint and What I Saw”**

---

# ❓ Quick Quiz

1. What is a breakpoint?
2. How do you add one in VS Code?
3. Why are breakpoints useful?

---

# 🤖 AI Tutor Prompts

* “Explain how breakpoints work in automation testing.”

---

# 💡 Lightbulb Reflection

**What was the most surprising part about using breakpoints?**

---

# 🎯 Interview Prep

**“How do you use breakpoints to debug automation tests?”**

---