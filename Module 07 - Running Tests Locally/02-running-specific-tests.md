# **Lesson 02 — Running Specific Tests**

> Module: **07 — Running Tests Locally**

---

# 🎯 Lesson Objective

You will learn:

* How to run a specific test file
* How to run a test block
* How to use `test.only` and `test.skip`
* How to speed up debugging

---

# 📝 Text Mode (Full Explanation)

### **Running a Specific File**

```
npx playwright test tests/login.spec.js
```

---

### **Running a Specific Test by Title**

```
npx playwright test -g "login test"
```

The `-g` flag filters tests by test name.

---

### **Using test.only**

Run only one test:

```js
test.only('this test only', async ({ page }) => {});
```

---

### **Using test.skip**

Skip a test:

```js
test.skip('skipped test', async ({ page }) => {});
```

---

# 🧪 Mini Code Challenge

Create a file with 2 tests.
Run only one of them.

---

# 📝 Assignment

Write:

**“3 Ways to Run Specific Tests and When I Would Use Them”**

---

# ❓ Quick Quiz

1. How do you run one test file?
2. What does `-g` do?
3. What is `test.only` used for?

---

# 🤖 AI Tutor Prompts

* “Show me how to run a single test with Playwright.”

---

# 💡 Lightbulb Reflection

**Which filtering method will you use most often?**

---

# 🎯 Interview Prep

**“How do you run a single test in Playwright?”**

---
