# **Lesson 04 — Launching the Browser**

> Module: **05 — Writing Your First Playwright Test**

---

# 🎯 Lesson Objective

You will understand:

* How Playwright launches browsers
* Browser context
* Page objects
* Why Playwright uses isolated environments

---

# 📝 Text Mode (Full Explanation)

### **How Browsers Launch in Playwright**

Playwright uses:

* **Browser** → The actual browser
* **Context** → Isolated session
* **Page** → A single tab

---

### **Why Playwright Uses Contexts**

Contexts allow:

✔ Isolated sessions
✔ No cookie sharing
✔ Fast parallel tests
✔ Predictable behavior

---

### **Example**

```
test('open browser', async ({ page }) => {
  await page.goto('https://example.com');
});
```

Playwright handles contexts automatically.

---

# 🧪 Mini Code Challenge

Identify:

* Browser
* Context
* Page

based on your test run.

---

# 📝 Assignment

Write:

**“How Playwright Launches Browsers — In My Words”**

---

# ❓ Quick Quiz

1. What is a browser context?
2. What is a page in Playwright?
3. Why is test isolation important?

---

# 🤖 AI Tutor Prompts

* “Explain browser-context-page simply.”

---

# 💡 Lightbulb Reflection

**Which part of the browser-context-page relationship makes the most sense?**

---

# 🎯 Interview Prep

**“Explain how Playwright launches and manages browser sessions.”**

---