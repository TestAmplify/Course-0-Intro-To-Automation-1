# **Lesson 05 — Running Tests in Parallel**

> Module: **07 — Running Tests Locally**

---

# 🎯 Lesson Objective

You will learn:

* What parallel testing is
* Why parallelism increases speed
* How Playwright manages parallel workers
* How to configure concurrency

---

# 📝 Text Mode (Full Explanation)

### **Parallel Execution**

Playwright runs tests in parallel by default.

Example outputs show:

```
3 workers
```

Each worker runs a test file simultaneously.

---

### **Configure Workers**

In config:

```js
workers: 4
```

Or run-time:

```
npx playwright test --workers=2
```

---

### **Why Parallel Testing Matters**

✔ Faster execution
✔ Scales horizontally
✔ Efficient in CI
✔ Ideal for large suites

---

# 🧪 Mini Code Challenge

Run:

```
npx playwright test --workers=1
```

Then:

```
npx playwright test --workers=4
```

Compare times.

---

# 📝 Assignment

Write:

**“Parallel Testing — Before and After Results”**

---

# ❓ Quick Quiz

1. Why is parallel testing useful?
2. What is a worker?
3. How do you configure workers?

---

# 🤖 AI Tutor Prompts

* “Explain parallel test execution simply.”

---

# 💡 Lightbulb Reflection

**How much faster were your tests with parallel workers?**

---

# 🎯 Interview Prep

**“How does Playwright handle parallel execution?”**

---