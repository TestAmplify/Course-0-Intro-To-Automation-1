# **Lesson 04 — Using Projects to Run Multiple Browsers**

> Module: **07 — Running Tests Locally**

---

# 🎯 Lesson Objective

Understand:

* What projects are
* How to configure multiple browsers
* How to run tests in different environments

---

# 📝 Text Mode (Full Explanation)

### **What Are Playwright Projects?**

A “project” represents a configuration.

Example:

* Chrome
* Firefox
* WebKit
* Mobile mode
* Different devices

---

### **Example Config**

```js
projects: [
  { name: 'chromium', use: { browserName: 'chromium' }},
  { name: 'firefox', use: { browserName: 'firefox' }},
  { name: 'webkit', use: { browserName: 'webkit' }},
]
```

---

### **Run All Projects**

```
npx playwright test
```

Tests run **in all browsers**.

---

### **Run One Project**

```
npx playwright test --project=chromium
```

---

# 🧪 Mini Code Challenge

Add Firefox to your playwright.config.js and run only Firefox tests.

---

# 📝 Assignment

Write:

**“How Playwright Uses Projects for Cross-Browser Testing”**

---

# ❓ Quick Quiz

1. What is a project in Playwright?
2. Which browsers can Playwright run tests in?
3. How do you run only Chromium tests?

---

# 🤖 AI Tutor Prompts

* “Explain Playwright projects with examples.”

---

# 💡 Lightbulb Reflection

**Which browser will you test most often—and why?**

---

# 🎯 Interview Prep

**“How do you run Playwright tests in different browsers?”**

---