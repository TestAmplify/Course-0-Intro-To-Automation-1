# **Lesson 03 — XPath Essential Basics**

> Module: **04 — Locators and Selectors**

---

# 🎯 Lesson Objective

Understand:

* What XPath is
* When XPath is useful
* When to avoid XPath
* Basic XPath syntax

---

# 📝 Text Mode (Full Explanation)

### **What Is XPath?**

XPath is a path query language used to navigate XML/HTML trees.

Example:

```
//*[@id="login-btn"]
```

---

### **Basic XPath Examples**

**Select by attribute:**

```
//*[@type="email"]
```

**Select by text:**

```
//*[text()="Login"]
```

**Select by tag:**

```
//button
```

---

### **When XPath Is Useful**

* Elements have no IDs
* Complex hierarchy
* Dynamic attributes

---

### **When to Avoid XPath**

* When CSS works
* When maintainability is important
* When tests need speed

CSS is generally preferred unless XPath is necessary.

---

# 🧪 Mini Code Challenge

Inspect an element → Write an XPath that selects it.

---

# 📝 Assignment

Write:

**“Three XPath Expressions I Can Use Today”**

---

# ❓ Quick Quiz

1. What is XPath?
2. When is XPath useful?
3. When should you avoid XPath?
4. Give one XPath example.

---

# 🤖 AI Tutor Prompts

* “Explain XPath simply.”
* “Compare CSS vs XPath for automation.”

---

# 💡 Lightbulb Reflection

**Do you prefer CSS or XPath so far? Why?**

---

# 🎯 Interview Prep

**“When would you use XPath instead of CSS?”**

---