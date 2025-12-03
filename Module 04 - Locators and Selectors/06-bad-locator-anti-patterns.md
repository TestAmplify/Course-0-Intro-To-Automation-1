# **Lesson 06 — Bad Locator Anti-Patterns**

> Module: **04 — Locators and Selectors**

---

# 🎯 Lesson Objective

You will learn:

* Common locator mistakes
* Why anti-patterns cause flaky tests
* How to rewrite bad locators into good ones

---

# 📝 Text Mode (Full Explanation)

### **Anti-Pattern #1 — Using nth-child**

```
button:nth-child(4)
```

Breaks whenever the UI changes.

---

### **Anti-Pattern #2 — Using Text That Changes**

```
page.getByText("Buy Now - 25% Off!")
```

Text changes frequently.

---

### **Anti-Pattern #3 — Relying on CSS classes for styling**

```
.button-blue
```

Classes often change during redesigns.

---

### **Anti-Pattern #4 — Using complex XPath unnecessarily**

```
/html/body/div[2]/div[1]/form/input
```

Highly fragile.

---

# 🧪 Mini Code Challenge

Find a bad locator on a webpage.
Rewrite it into a stable alternative.

---

# 📝 Assignment

Write:

**“Locator Anti-Patterns I Will Avoid”**

---

# ❓ Quick Quiz

1. Why is nth-child unstable?
2. Why is styling-based CSS bad for automation?
3. What is wrong with long XPath?

---

# 🤖 AI Tutor Prompts

* “Rewrite this bad locator into a stable one: [paste any].”

---

# 💡 Lightbulb Reflection

**Which anti-pattern were you most guilty of before this lesson?**

---

# 🎯 Interview Prep

**“Give examples of bad locators.”**

---