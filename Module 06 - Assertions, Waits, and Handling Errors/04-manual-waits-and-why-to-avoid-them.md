# **Lesson 04 — Manual Waits and Why to Avoid Them**

> Module: **06 — Assertions, Waits, and Handling Errors**

---

# 🎯 Lesson Objective

Learn:

* What manual waits are
* Why manual waits are dangerous
* When (rarely) manual waits can be used
* How to replace manual waits with stable methods

---

# 📝 Text Mode (Full Explanation)

### **What Are Manual Waits?**

Manual waits force the test to pause:

```
await page.waitForTimeout(3000);
```

This pauses execution for 3 seconds.

---

### **Why Manual Waits Are Bad**

❌ Slow tests
❌ Still flaky
❌ Depend on timing
❌ Don’t adapt to load speed
❌ Break when UI changes

---

### **Better Alternatives**

Use:

* Assertions
* Auto-waiting
* Locator-based waits

Example:

```
await expect(page.getByText('Dashboard')).toBeVisible();
```

---

### **When Manual Waits Are Acceptable (Rare)**

* Debugging
* Demonstrations
* Visual observation

Never use in production tests.

---

# 🧪 Mini Code Challenge

Rewrite this:

```
await page.waitForTimeout(5000);
```

Into a **better** Playwright wait.

---

# 📝 Assignment

Write:

**“Why I Will Avoid Manual Waits”**

---

# ❓ Quick Quiz

1. What does `waitForTimeout()` do?
2. Why is it a bad practice?
3. What is a better alternative?

---

# 🤖 AI Tutor Prompts

* “Rewrite this manual wait into a correct auto-wait.”

---

# 💡 Lightbulb Reflection

**Why do you think many beginners overuse manual waits?**

---

# 🎯 Interview Prep

**“Why should you avoid manual waits in automation?”**

---