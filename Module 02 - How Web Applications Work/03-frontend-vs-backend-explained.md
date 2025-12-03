# ✅ **Lesson 03 — Frontend vs Backend Explained**

> Module: **02 — How Web Applications Work**

---

# 🎯 Lesson Objective

By the end of this lesson, you will understand:

* The difference between frontend and backend
* How both work together
* Why automation tests must consider both
* What parts of the app Playwright interacts with

---

# 📝 Text Mode (Full Explanation)

### **Frontend (Client-Side)**

Everything the user sees:

* HTML
* CSS
* JavaScript
* Buttons
* Inputs
* Forms
* Images

Automation interacts heavily with the frontend via the DOM.

---

### **Backend (Server-Side)**

Everything the user **does not** see:

* Databases
* APIs
* Authentication
* Business logic
* Servers

Automation sometimes verifies backend behavior via API tests.

---

### **How They Work Together**

Example:

1. User clicks “Login” (frontend)
2. Browser sends data to server (request)
3. Server checks credentials (backend)
4. Server responds with success/failure
5. Frontend updates accordingly

Automation must verify this flow works.

---

### **Why This Matters**

Automation tests often catch:

* Incorrect UI updates
* Broken backend logic
* API failures
* Slow processing times

Both sides must be understood to design effective tests.

---

# 🧪 Mini Code Challenge

List 3 things that belong to the frontend
List 3 things that belong to the backend

---

# 📝 Assignment

In your own words, write:

**“How the Frontend and Backend Work Together”**

---

# ❓ Quick Quiz

1. What is frontend?
2. What is backend?
3. Give one example of each.
4. Which one does Playwright directly interact with?
5. Which one handles authentication?

---

# 🤖 AI Tutor Prompts

* “Explain frontend vs backend in simple terms.”
* “Give me examples of frontend and backend tasks.”
* “How does automation interact with both?”

---

# 💡 Lightbulb Reflection

**Which side (frontend or backend) do you feel more comfortable with so far?**

---

# 🎯 Interview Prep

**“Explain frontend vs backend to a non-technical person.”**

---