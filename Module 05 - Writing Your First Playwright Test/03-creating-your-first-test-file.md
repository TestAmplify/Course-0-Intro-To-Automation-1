# **Lesson 03 — Creating Your First Test File**

> Module: **05 — Writing Your First Playwright Test**

---

# 🎯 Lesson Objective

You will learn:

* How to create a test file
* How Playwright organizes tests
* Basic test syntax
* How to run a single test

---

# 📝 Text Mode (Full Explanation)

### **Create a New Test File**

Inside the `tests/` folder, create:

```
first-test.spec.js
```

---

### **Basic Test Syntax**

Inside the file:

```
import { test, expect } from '@playwright/test';

test('my first test', async ({ page }) => {
  await page.goto('https://www.google.com');
  await expect(page).toHaveTitle(/Google/);
});
```

---

### **Run the Test**

```
npx playwright test tests/first-test.spec.js
```

If everything is set up:

✔ Browser launches
✔ Page loads
✔ Test passes

---

# 🧪 Mini Code Challenge

Create a test that checks the title of any website.

---

# 📝 Assignment

Write:

**“My First Playwright Test — What I Observed”**

---

# ❓ Quick Quiz

1. What command runs a single Playwright test file?
2. What function is used to define a test?
3. What is `expect()` used for?

---

# 🤖 AI Tutor Prompts

* “Explain basic Playwright test syntax.”
* “Why does Playwright pass the page object automatically?”

---

# 💡 Lightbulb Reflection

**How did it feel to write your very first automation test?**

---

# 🎯 Interview Prep

**“Write a simple test that navigates to a URL and checks its title.”**

---