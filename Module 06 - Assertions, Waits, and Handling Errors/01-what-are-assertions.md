# **Lesson 01 — What Are Assertions?**

> Module: **06 — Assertions, Waits, and Handling Errors**
> Track: **Test Automation Engineer — Course 0**

---

# 🎯 Lesson Objective

By the end of this lesson, you will clearly understand:

* What assertions are
* Why assertions are essential in automation
* How assertions validate expected behavior
* The difference between soft and hard assertions
* How assertions catch bugs early

---

# 📝 Text Mode (Full Explanation)

### **What Is an Assertion?**

An assertion is a **statement that must be true** for a test to pass.

Example:

> “The page title should contain the word ‘Login’.”

If the condition is false → the test fails.

---

### **Assertion Example**

```
await expect(page).toHaveTitle(/Google/);
```

If Google changes the title → your test catches it.

---

### **Why Assertions Matter**

Assertions:

✔ Validate correct behavior
✔ Catch unexpected changes
✔ Enforce business rules
✔ Prevent silent failures

Without assertions, a test would not know what's “right.”

---

### **Hard vs Soft Assertions**

**Hard Assertions:**
Fail the test immediately.

**Soft Assertions:**
Collect failures and continue execution.

---

# 🧪 Mini Code Challenge

Write one assertion that checks:

* The URL contains something specific
* A button is visible

---

# 📝 Assignment

Write:

**“What I Learned About Assertions”**

---

# ❓ Quick Quiz

1. What is an assertion?
2. What happens when an assertion fails?
3. What is the difference between hard and soft assertions?

---

# 🤖 AI Tutor Prompts

* “Explain assertions like I’m new to automation.”

---

# 💡 Lightbulb Reflection

**Why do you think assertions are important in testing?**

---

# 🎯 Interview Prep

**“What is an assertion in automation testing?”**

---