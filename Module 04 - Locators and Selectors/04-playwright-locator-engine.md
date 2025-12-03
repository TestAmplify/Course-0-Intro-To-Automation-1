# **Lesson 04 — Playwright Locator Engine**

> Module: **04 — Locators and Selectors**

---

# 🎯 Lesson Objective

Understand:

* Playwright’s advanced locator engine
* Auto-waiting
* How Playwright chooses elements
* Best practices

---

# 📝 Text Mode (Full Explanation)

### **Playwright’s Locator Engine**

Playwright provides **smart locators**, such as:

```
page.getByRole()
page.getByText()
page.getByLabel()
page.getByPlaceholder()
```

These are more stable than raw CSS or XPath.

---

### **Why Playwright Locators Are Better**

* Auto-waiting
* Role-based selection
* Accessible
* More readable
* Resilient to DOM changes

---

### **Example**

```
await page.getByRole('button', { name: 'Login' }).click();
```

This is stable and human-readable.

---

# 🧪 Mini Code Challenge

Find a button on a sample site.
Write a Playwright locator using:

* `getByRole`
* `getByText`

---

# 📝 Assignment

Write:

**“Why Playwright Locators Are My Default Choice”**

---

# ❓ Quick Quiz

1. What is `getByRole` used for?
2. Why are Playwright locators stable?
3. What does auto-waiting do?

---

# 🤖 AI Tutor Prompts

* “Explain Playwright locators in simple terms.”
* “Why are Playwright locators better than CSS?”

---

# 💡 Lightbulb Reflection

**Which Playwright locator feels most useful so far?**

---

# 🎯 Interview Prep

**“What is Playwright’s locator engine?”**

---