# **Lesson 02 — Understanding Project Structure**

> Module: **05 — Writing Your First Playwright Test**

---

# 🎯 Lesson Objective

You will understand:

* The structure of a Playwright project
* What each folder and file does
* Where tests live
* Where config lives
* What the example test is for

---

# 📝 Text Mode (Full Explanation)

### **After installing Playwright, your project looks like this:**

```
playwright.config.js
tests/
  example.spec.js
tests-examples/
  demo-todo-app.spec.js
```

---

### **Key Files**

**`playwright.config.js`**
The main configuration file.
Controls:

* Browsers
* Timeouts
* Reporter settings
* Parallelism
* Test directory

---

### **tests/ folder**

Where **your** test files go.

Example:

```
tests/login.spec.js
tests/cart.spec.js
tests/profile.spec.js
```

---

### **tests-examples folder**

Sample tests created when you installed Playwright.
You can delete them later.

---

### **Why This Matters**

Automation engineers must know where:

* Tests live
* Config lives
* Reports live
* Screenshots go

A clean structure prevents confusion and keeps tests maintainable.

---

# 🧪 Mini Code Challenge

Open your project folder.
Locate:

* `playwright.config.js`
* `tests/` folder
* Example test file

---

# 📝 Assignment

Write:

**“Understanding My Playwright Project Structure”**

List each important file and its purpose.

---

# ❓ Quick Quiz

1. What is the purpose of `playwright.config.js`?
2. Where do test files go?
3. What is inside tests-examples?

---

# 🤖 AI Tutor Prompts

* “Explain the Playwright project structure to me.”

---

# 💡 Lightbulb Reflection

**Which part of the project structure makes the most sense to you?**

---

# 🎯 Interview Prep

**“Explain the structure of a Playwright project.”**

---