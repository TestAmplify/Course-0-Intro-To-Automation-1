# **Lesson 03 — Debug Console and Logs**

> Module: **08 — Understanding VS Code Debugging Tools**

---

# 🎯 Lesson Objective

Understand:

* How the Debug Console works
* How to print values using console logs
* How to inspect errors
* How to validate locator results

---

# 📝 Text Mode (Full Explanation)

### **Debug Console**

The Debug Console shows:

* Console logs from the test
* Errors
* Variable values
* Network errors
* Playwright logs (if enabled)

---

### **Using console.log()**

You can print information to the console during test execution.

Example:

```
console.log('Page title:', await page.title());
```

This helps validate what the browser sees.

---

### **Why Logging Helps Debugging**

✔ Confirms element values
✔ Reveals unexpected page behavior
✔ Shows where failures occur
✔ Helps verify script flow

---

# 🧪 Mini Code Challenge

Add a console log that prints:

* Current URL
* Page title

Run the test and confirm output.

---

# 📝 Assignment

Write:

**“How Debug Console Helped Me Understand My Test”**

---

# ❓ Quick Quiz

1. What does the Debug Console show?
2. How do you print logs?
3. Why are logs helpful?

---

# 🤖 AI Tutor Prompts

* “Help me debug my console logs in Playwright.”

---

# 💡 Lightbulb Reflection

**What did you learn by printing logs today?**

---

# 🎯 Interview Prep

**“How do you use logs to debug tests?”**

---