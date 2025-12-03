# **Lesson 06 — Interacting With Elements**

> Module: **05 — Writing Your First Playwright Test**

---

# 🎯 Lesson Objective

You will learn:

* How to click elements
* How to type text
* How to fill input fields
* How Playwright handles interactions

---

# 📝 Text Mode (Full Explanation)

### **Click Example**

```
await page.getByRole('button', { name: 'Login' }).click();
```

---

### **Type Example**

```
await page.locator('#email').type('toby@test.com');
```

---

### **Fill Example**

```
await page.fill('#password', 'Test1234!');
```

---

### **Select Example**

```
await page.selectOption('#country', 'USA');
```

---

### **Checkbox Example**

```
await page.check('#agree');
```

---

# 🧪 Mini Code Challenge

Write a test that:

* Opens a webpage
* Types text
* Clicks a button

---

# 📝 Assignment

Write:

**“Interactions I Practiced Today”**

---

# ❓ Quick Quiz

1. How do you click a button?
2. How do you type text?
3. How do you select a dropdown option?

---

# 🤖 AI Tutor Prompts

* “Explain difference between type() and fill().”

---

# 💡 Lightbulb Reflection

**Which interaction felt easiest to understand?**

---

# 🎯 Interview Prep

**“Show me how to fill out a form using Playwright.”**

---