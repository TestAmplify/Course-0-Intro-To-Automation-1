# **Lesson 01 — What Are Locators?**

> Module: **04 — Locators and Selectors**
> Track: **Test Automation Engineer — Course 0**

---

# 🎯 Lesson Objective

By the end of this lesson, you will clearly understand:

* What locators are
* Why automation frameworks rely on locators
* How locators identify elements on a webpage
* Why stable locators prevent flaky tests
* How Playwright uses locators internally

---

# 📝 Text Mode (Full Explanation)

### **What Is a Locator?**

A locator is a **way to identify a specific element** in the DOM so automation tools know:

* What to click
* Where to type
* What to check
* Which element is correct

Examples of elements you may want to locate:

* A login button
* A text box
* A menu item
* A label
* A submit button

Locators tell Playwright **which element** to interact with.

---

### **Why Locators Are Important**

A bad locator → flaky test
A good locator → stable test

Locators should be:

✔ Unique
✔ Stable
✔ Predictable
✔ Not dependent on animations
✔ Not dependent on position

---

### **Playwright’s Locator Concept**

Playwright uses the **Locator API**, which:

* Auto-waits
* Tracks element states
* Handles dynamic DOM changes

Example:

```
await page.getByRole('button', { name: 'Login' }).click();
```

This is more reliable than raw CSS or XPath.

---

# 🧪 Mini Code Challenge

Open DevTools → Inspect a button.

Write down:

* Tag name
* ID
* Class
* Text

---

# 📝 Assignment

Write:

**“What Is a Locator and Why It Matters in Automation”**

---

# ❓ Quick Quiz

1. What is a locator?
2. Why is locator stability important?
3. What does Playwright use to find elements?
4. What causes flaky locators?

---

# 🤖 AI Tutor Prompts

* “Explain locators like I'm new to automation.”
* “What makes a locator stable?”
* “Why should I avoid position-based locators?”

---

# 💡 Lightbulb Reflection

**What did you learn about locators that you didn’t know before?**

---

# 🎯 Interview Prep

**“What is a locator?”**

---