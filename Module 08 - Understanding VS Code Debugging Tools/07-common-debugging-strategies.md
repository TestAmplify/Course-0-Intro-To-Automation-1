# **Lesson 07 — Common Debugging Strategies**

> Module: **08 — Understanding VS Code Debugging Tools**

---

# 🎯 Lesson Objective

Understand:

* Practical debugging strategies
* How to isolate failures
* How to fix locator problems
* How to debug dynamic DOMs

---

# 📝 Text Mode (Full Explanation)

### **Top Debugging Techniques**

**1. Use UI Mode**
Replay tests visually.

**2. Use `page.pause()`**
Stop the test instantly.

**3. Use console logs**
Print values during test execution.

**4. Inspect DOM changes**
Use DevTools + Inspector.

**5. Isolate failing tests**

```
test.only(...)
```

**6. Debug locator issues**
Highlight elements in Inspector.

---

### **Common Debugging Flow**

1. Run failing test
2. View HTML report
3. Open Trace Viewer
4. Reproduce locally
5. Pause test
6. Inspect DOM
7. Fix locator or wait
8. Re-run test

---

# 🧪 Mini Code Challenge

Take a failing test.
Use **two debugging strategies** to understand the issue.

---

# 📝 Assignment

Write:

**“My Debugging Strategy for Fixing a Failed Test”**

---

# ❓ Quick Quiz

1. What is the purpose of isolating failures?
2. Why is `page.pause()` useful?
3. Why inspect the DOM?

---

# 🤖 AI Tutor Prompts

* “Give me a debugging plan for a failing Playwright test.”

---

# 💡 Lightbulb Reflection

**Which debugging strategy do you think will help you the most?**

---

# 🎯 Interview Prep

**“How do you debug a failing automation test?”**

---