# **Lesson 05 — Navigating to a Webpage**

> Module: **05 — Your First Playwright Test**

---

# 🎯 Lesson Objective

You will learn:

* How navigation works
* Using `page.goto()`
* How to wait for page load events
* Navigation failures

---

# 📝 Text Mode (Full Explanation)

### **Navigate to a Page**

```
await page.goto('https://mini-shop.testamplify.com');
```

---

### **Waiting for the Page to Load**

Playwright auto-waits for:

* DOMContentLoaded
* Network to be idle
* Page to stabilize

This reduces flakiness.

---

### **Navigation Failures**

Happen when:

* URL is wrong
* Server is down
* SSL issues
* Redirect loops

Playwright gives clear error messages.

---

# 🧪 Mini Code Challenge

Navigate to any URL and print the page title.

---

# 📝 Assignment

Write:

**“What I Learned About Page Navigation”**

---

# ❓ Quick Quiz

1. What does `page.goto()` do?
2. What does Playwright wait for automatically?
3. Why do navigation errors happen?

---

# 🤖 AI Tutor Prompts

* “Explain how Playwright handles page navigation.”

---

# 💡 Lightbulb Reflection

**What surprised you about navigation auto-waiting?**

---

# 🎯 Interview Prep

**“Explain how page navigation works in Playwright.”**

---
