# **Lesson 02 — Playwright Built-In Assertions**

> Module: **06 — Assertions, Waits, and Handling Errors**

---

# 🎯 Lesson Objective

You will learn:

* The built-in assertion library in Playwright
* Commonly used Playwright assertions
* How Playwright auto-waits for assertions
* Best practices for writing stable assertions

---

# 📝 Text Mode (Full Explanation)

### **Playwright Assertion Examples**

**Check title:**

```
await expect(page).toHaveTitle(/Example/);
```

**Check URL:**

```
await expect(page).toHaveURL(/login/);
```

**Check element visibility:**

```
await expect(locator).toBeVisible();
```

**Check text content:**

```
await expect(locator).toHaveText('Login');
```

**Check count:**

```
await expect(locator).toHaveCount(3);
```

---

### **Why Playwright Assertions Are Reliable**

Playwright auto-waits for:

✔ Element to appear
✔ Element to become stable
✔ Page to finish loading
✔ Network to be idle

This reduces flakiness.

---

# 🧪 Mini Code Challenge

Write assertions for:

* Page title
* A visible header
* A button’s text

---

# 📝 Assignment

Write:

**“Three Playwright Assertions I Can Use Today”**

---

# ❓ Quick Quiz

1. What does `toBeVisible()` check?
2. What does Playwright auto-wait for?
3. Why are Playwright assertions better than manual waits?

---

# 🤖 AI Tutor Prompts

* “Explain Playwright’s auto-waiting in assertions.”

---

# 💡 Lightbulb Reflection

**Which assertion will you use most often?**

---

# 🎯 Interview Prep

**“What are some Playwright assertions you’ve used?”**

---

---

