# ✅ **Lesson 02 — What Happens When You Visit a Website**

> Module: **02 — How Web Applications Work**
> Track: **Test Automation Engineer — Course 0**

---

# 🎯 Lesson Objective

By the end of this lesson, you will understand:

* The browser’s step-by-step process when loading a webpage
* DNS lookup
* Server communication
* Page rendering
* How this impacts automation timing and waits

---

# 📝 Text Mode (Full Explanation)

### **Step 1 — You Enter a URL**

Example:

```
https://www.testamplify.com
```

---

### **Step 2 — DNS Lookup**

DNS acts like the internet’s phonebook.

It converts:

`www.testamplify.com` → an IP address (e.g., `142.250.190.78`)

Automation engineers must know this because DNS delays impact test speed.

---

### **Step 3 — Browser Sends a Request**

A request is sent to the server containing:

* Browser info
* URL
* Cookies
* Headers

---

### **Step 4 — Server Processes and Responds**

The server responds with:

* HTML
* CSS
* JavaScript
* Images
* Data

---

### **Step 5 — Browser Renders the Page**

Rendering means:

* Building the DOM
* Applying styles
* Running scripts
* Showing content

Automation waits for these steps to complete.

---

### **Why This Matters to Test Automation**

Timing issues in automation usually come from:

* Slow rendering
* Delayed scripts
* Late-loaded components
* Dynamic content

This is why Playwright’s auto-waiting is powerful — it waits for elements to be ready.

---

# 🧪 Mini Code Challenge

Open DevTools → **Performance** tab → Refresh the page.

Identify:

* DNS time
* Request time
* Rendering time

---

# 📝 Assignment

Write:

**“Steps My Browser Takes When Loading a Website”**

Include 4–6 steps in your own words.

---

# ❓ Quick Quiz

1. What does DNS do?
2. What does the server send back to the browser?
3. What is rendering?
4. Why do automation engineers care about rendering time?

---

# 🤖 AI Tutor Prompts

* “Explain DNS lookup in simple terms.”
* “Why does rendering affect automation waits?”
* “Break down the browser loading steps.”

---

# 💡 Lightbulb Reflection

**What step of the webpage loading process surprised you the most?**

---

# 🎯 Interview Prep

**“Explain what happens in the browser when you visit a website.”**

---