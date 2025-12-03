# **Lesson 07 — Local Test Configuration**

> Module: **07 — Running Tests Locally**

---

# 🎯 Lesson Objective

You will understand:

* How to customize Playwright config
* Timeout settings
* Reporter configuration
* Browser and device settings

---

# 📝 Text Mode (Full Explanation)

### **Common Config Options**

```
timeout: 30000,
retries: 1,
use: {
  headless: true,
  viewport: { width: 1280, height: 720 },
},
reporter: [['html']]
```

---

### **Why Configuration Matters**

Config allows you to:

✔ Control environments
✔ Improve speed
✔ Reduce flakiness
✔ Set consistent behavior

---

### **Examples**

**Set a custom timeout:**

```
timeout: 20000
```

**Enable trace on failure:**

```
use: { trace: 'on-first-retry' }
```

---

# 🧪 Mini Code Challenge

Add:

```
retries: 1
```

to your config and re-run a failing test.

---

# 📝 Assignment

Write:

**“3 Local Config Settings I Used Today”**

---

# ❓ Quick Quiz

1. What does `timeout` control?
2. What does `retries` do?
3. What config sets headless mode?

---

# 🤖 AI Tutor Prompts

* “Explain common Playwright config settings.”

---

# 💡 Lightbulb Reflection

**Which config setting do you think is most helpful?**

---

# 🎯 Interview Prep

**“How do you configure Playwright for local execution?”**

---