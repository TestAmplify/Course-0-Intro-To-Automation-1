# ✅ **Lesson 05 — APIs and How Frontend Talks to Backend**

> Module: **02 — How Web Applications Work**

---

# 🎯 Lesson Objective

By the end of this lesson, you will understand:

* What an API is
* How the frontend communicates with the backend
* What JSON is
* Why automation engineers must understand APIs

---

# 📝 Text Mode (Full Explanation)

### **What Is an API?**

API = **Application Programming Interface**

It allows two systems to talk to each other.

Example:

Frontend → API → Backend → Database

---

### **APIs in Web Applications**

Common tasks:

* Login
* Sign up
* Fetching data
* Submitting forms
* Updating user information

Automation tests often involve verifying UI + backend together.

---

### **JSON Responses**

APIs commonly return JSON:

```
{
  "user": "Toby",
  "role": "admin"
}
```

Automation tests sometimes validate backend responses.

---

### **Why This Matters for Automation**

Automation engineers must know:

* How UI triggers API calls
* How API failures affect the UI
* How to debug API-related test failures
* How to test APIs directly (later module)

---

# 🧪 Mini Code Challenge

Open DevTools → Network → Filter by **XHR**

Observe:

* API URL
* Request method
* Response status
* JSON response

---

# 📝 Assignment

Write:

**“How APIs Support Web Applications”**

Include one real example you observed.

---

# ❓ Quick Quiz

1. What is an API?
2. What format are API responses usually in?
3. Which DevTools tab shows API calls?
4. Why are APIs important in automation?

---

# 🤖 AI Tutor Prompts

* “Explain how frontend communicates with backend.”
* “What is JSON and why do APIs use it?”
* “How do I inspect API calls in DevTools?”

---

# 💡 Lightbulb Reflection

**What did you learn about APIs today that you didn’t know before?**

---

# 🎯 Interview Prep

**“Explain what an API is in simple terms.”**

---