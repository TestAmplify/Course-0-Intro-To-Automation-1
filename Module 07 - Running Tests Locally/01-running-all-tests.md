# **Lesson 01 — Running All Tests**

> Module: **07 — Running Tests Locally**
> Track: **Test Automation Engineer — Course 0**

---

# 🎯 Lesson Objective

By the end of this lesson, you will know:

* How to run all Playwright tests at once
* What the default test runner does
* How Playwright manages execution flow
* How to read results from the terminal

---

# 📝 Text Mode (Full Explanation)

### **How to Run All Tests**

Use the Playwright test command:

```
npx playwright test
```

This command:

✔ Finds all tests in the `tests/` folder
✔ Runs them in parallel
✔ Uses your config settings
✔ Generates reports

---

### **What Happens When Tests Run**

Playwright will:

* Launch browsers
* Create isolated contexts
* Execute each test file
* Output pass/fail results
* Save traces/screenshots (if configured)

---

### **Why Run All Tests Locally**

* Quick feedback
* Smoke testing
* Regression checks
* Preparing for CI/CD

---

# 🧪 Mini Code Challenge

Run:

```
npx playwright test
```

Observe:

* Number of tests
* Pass/Fail summary
* Runtime

---

# 📝 Assignment

Write:

**“My Experience Running All Tests Locally”**

---

# ❓ Quick Quiz

1. What command runs all Playwright tests?
2. Where does Playwright look for test files?
3. What does the test summary show?

---

# 🤖 AI Tutor Prompts

* “Explain what happens internally when Playwright runs all tests.”

---

# 💡 Lightbulb Reflection

**What surprised you about the test runner output?**

---

# 🎯 Interview Prep

**“How do you run all tests in Playwright?”**

---