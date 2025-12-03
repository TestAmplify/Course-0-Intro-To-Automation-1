# **Lesson 07 — Advanced Locators: getByRole, getByText, has, nth**

> Module: **04 — Locators and Selectors**

---

# 🎯 Lesson Objective

Learn how to use the **most powerful Playwright locators**, including:

* `getByRole()`
* `getByText()`
* `locator().nth()`
* `locator().filter({ has: … })`

---

# 📝 Text Mode (Full Explanation)

### **getByRole()**

Best for buttons, links, headings:

```
page.getByRole('button', { name: 'Login' });
```

---

### **getByText()**

Matches visible text:

```
page.getByText('Submit');
```

---

### **nth()**

Used when multiple matching elements exist:

```
page.getByRole('button').nth(2);
```

---

### **has()**

Target elements containing other elements:

```
page.locator('div.card').filter({ has: page.locator('button') });
```

---

# 🧪 Mini Code Challenge

Write:

* One `getByRole` locator
* One `getByText` locator
* One locator using `nth()`

---

# 📝 Assignment

Write:

**“Advanced Locators I Can Use Today”**

---

# ❓ Quick Quiz

1. When to use `getByRole`?
2. When to use `nth()`?
3. Why is `getByText` useful?

---

# 🤖 AI Tutor Prompts

* “Explain how to choose between getByRole and getByText.”

---

# 💡 Lightbulb Reflection

**Which advanced locator feels most powerful to you?**

---

# 🎯 Interview Prep

**“Explain advanced Playwright locator strategies.”**

---