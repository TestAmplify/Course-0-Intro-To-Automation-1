# **Lesson 06 — Debugging Failed Tests**

> Module: **06 — Assertions, Waits, and Handling Errors**

---

# 🎯 Lesson Objective

You will learn:

* How to debug Playwright tests
* How to use trace viewer
* How to re-run failed tests
* How to inspect failure logs

---

# 📝 Text Mode (Full Explanation)

### **Debugging Tools in Playwright**

**1. UI Mode**

```
npx playwright test --ui
```

**2. Trace Viewer**

```
npx playwright show-trace trace.zip
```

**3. Debug Mode**

```
PWDEBUG=1 npx playwright test
```

---

### **Why Debugging Tools Matter**

They help you:

* See what the test saw
* Replay test execution
* Inspect failed steps
* View DOM snapshots
* Analyze console and network logs

---

# 🧪 Mini Code Challenge

Run:

```
npx playwright test --ui
```

Open the failed test → explore DOM snapshots.

---

# 📝 Assignment

Write:

**“How I Used Playwright Debugging for the First Time”**

---

# ❓ Quick Quiz

1. What command opens UI mode?
2. What does trace viewer show?
3. Why is debugging essential?

---

# 🤖 AI Tutor Prompts

* “Explain how to debug Playwright tests effectively.”

---

# 💡 Lightbulb Reflection

**Which debugging tool felt most useful to you?**

---

# 🎯 Interview Prep

**“How do you debug failed Playwright tests?”**

---