# **Lesson 02 — Installing Node.js (LTS)**

> Module: **01 — Installing Node.js and VS Code**
> Track: **Test Automation Engineer — Course 0 (Intro to Automation Testing)**

---

# 🎯 Lesson Objective

By the end of this lesson, you will clearly understand:

* What Node.js is and why automation depends on it
* Why the LTS version is required
* How to install Node.js correctly
* How to verify installation
* What npm is and why Playwright needs it

Node.js is the engine that powers all JavaScript-based automation frameworks, including Playwright.

---

# 📝 Text Mode (Full Explanation)

### **What Is Node.js?**

Node.js is a **JavaScript runtime** that allows you to run JavaScript **outside of a browser**.

This is important because automation tools like **Playwright** run on your machine, not inside Chrome or Edge.

Node.js allows automation tools to:

* Launch browsers
* Run tests
* Execute JavaScript scripts
* Install automation packages
* Handle test reports

Without Node.js → Playwright cannot run.

---

### **Why Use the LTS Version?**

LTS means **Long-Term Support**, which gives you:

✔ Stability
✔ Fewer breaking changes
✔ Enterprise-grade reliability
✔ Official support

Automation engineers always install **Node.js LTS** — never the “Current” version.

---

### **Installing Node.js (LTS)**

Follow these steps:

1. Visit: **[https://nodejs.org](https://nodejs.org)**
2. Click the **LTS (Recommended)** download button
3. Run the installer
4. Keep all settings as default
5. Complete installation

No special configuration is required.

---

### **How to Verify Node.js Installation**

Open your terminal (Mac) or Command Prompt/PowerShell (Windows) and type:

```
node -v
```

If installed correctly, you will see something like:

```
v18.xx.x
```

Then check npm:

```
npm -v
```

Expected output:

```
9.xx.x
```

If both commands return a version → ✔ Node.js is successfully installed.

---

### **What Is npm?**

`npm` stands for **Node Package Manager**.

It allows you to install automation tools like Playwright:

```
npm install -D @playwright/test
```

You will use npm frequently throughout this course.

---

# 🧪 Mini Code Challenge

Run the following in your terminal:

```
node -v
npm -v
```

Confirm that both show version numbers.

---

# 📝 Assignment

Create a short note titled:

**“My Node.js Setup Confirmation”**

Include:

1. Your Node.js version
2. Your npm version
3. Why Node.js is required for Playwright
4. A screenshot of your version output

Share your reflection with the instructor or on Slack/Pumble.

---

# ❓ Quick Quiz

1. What is Node.js?
2. Why should we install the LTS version?
3. What is npm used for?
4. How do you check if Node.js installed correctly?
5. Why do automation tools depend on Node.js?

---

# 🤖 AI Tutor Prompts

Use these prompts inside Skila/TestAmplify AI:

* “Explain Node.js like I’m brand new to tech.”
* “Why does Playwright require Node.js?”
* “What is the difference between Node.js and npm?”
* “What does LTS mean and why is it recommended?”

---

# 💡 Lightbulb Reflection

Take 1–2 minutes and answer:

**What is one new thing you learned about Node.js today?**

---

# 🎯 Interview Prep

Practice answering:

**“What is Node.js, and why is it important in test automation?”**

Keep it under **30 seconds**.

---
