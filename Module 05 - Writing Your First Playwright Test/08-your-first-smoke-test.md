# **Lesson 08 — Your First Smoke Test**

> Module: **05 — Writing Your First Playwright Test**

---

# 🎯 Lesson Objective

You will build:

* Your FIRST real automation test
* A basic smoke test using Playwright
* A test you will showcase in interviews

---

# 📝 Text Mode (Full Explanation)

### **What Is a Smoke Test?**

A smoke test checks:

* Site loads
* Page title is correct
* Key elements exist
* No obvious errors

Simple but powerful.

---

### **Example Playwright Smoke Test**

```
import { test, expect } from '@playwright/test';

test('basic smoke test', async ({ page }) => {
  await page.goto('https://example.com');
  await expect(page).toHaveTitle(/Example Domain/);
  await expect(page.getByRole('heading')).toBeVisible();
});
```

---

### **Why Smoke Tests Matter**

✔ Validate website availability
✔ Catch major issues
✔ Fast feedback
✔ Great for CI/CD
✔ Ideal for beginners

---

# 🧪 Mini Code Challenge

Write your own smoke test for any website:

* Navigate
* Verify title
* Verify an element

---

# 📝 Assignment

Write:

**“My First Smoke Test”**

Include:

* Code
* Screenshot of passing result

---

# ❓ Quick Quiz

1. What is a smoke test?
2. What should a smoke test validate?
3. Why do companies use smoke tests?

---

# 🤖 AI Tutor Prompts

* “Help me design a smoke test for a login page.”

---

# 💡 Lightbulb Reflection

**How did it feel to complete your first real automation test?**

---

# 🎯 Interview Prep

**“Write a simple smoke test for any webpage.”**

---