# ✅ **Lesson 07 — Verifying Your Installation**

> Module: **01 — Installing Node.js and VS Code**
> Track: **Test Automation Engineer — Course 0 (Intro to Automation Testing)**

---

# 🎯 Lesson Objective

By the end of this lesson, you will clearly understand:

* How to verify Node.js installation
* How to verify npm installation
* How to confirm Playwright installation
* How to ensure VS Code is fully configured
* How to confirm your automation environment is ready

This is the final validation step before writing your first automated test.

---

# 📝 Text Mode (Full Explanation)

### **Step 1 — Verify Node.js**

Open your terminal and run:

```
node -v
```

Expected output:

```
v18.xx.x  (or similar LTS version)
```

If you see a version number → ✔ Node.js is installed.

---

### **Step 2 — Verify npm**

Run:

```
npm -v
```

Expected output:

```
9.xx.x
```

If the version appears → ✔ npm is working.

---

### **Step 3 — Verify Playwright Installation**

Run:

```
npx playwright --version
```

Expected output:

```
Version 1.xx.x
```

If you see a version → ✔ Playwright is installed.

---

### **Step 4 — Run the Playwright Sample Test**

Inside your project folder, run:

```
npx playwright test
```

If installed correctly:

✔ A browser will launch
✔ The example test will run
✔ A success message will appear

This confirms Playwright is fully operational.

---

### **Step 5 — Verify VS Code Setup**

Inside VS Code:

* Check the terminal (View → Terminal)
* Confirm you can run:

  ```
  node -v
  ```
* Check that you installed the extensions earlier:

  * Playwright Test
  * Prettier
  * ESLint

If these work → ✔ VS Code is ready.

---

### **You Now Have a Fully Working Automation Environment**

Your setup now includes:

* Node.js
* npm
* VS Code
* Git
* Playwright
* Folder structure
* Installed browsers
* Working test commands

You are officially ready for **Module 02**, where real automation begins.

---

# 🧪 Mini Code Challenge

Run all of the following and confirm output:

```
node -v
npm -v
npx playwright --version
npx playwright test
```

Take screenshots of each result.

---

# 📝 Assignment

Create a note titled:

**“My Environment Verification Results”**

Include:

1. Output of `node -v`
2. Output of `npm -v`
3. Playwright version
4. Screenshot of running `npx playwright test`
5. Confirmation that VS Code extensions are installed

Share with your instructor or Slack/Pumble.

---

# ❓ Quick Quiz

1. How do you check your Node.js version?
2. How do you check if Playwright is installed?
3. What command runs the sample Playwright test?
4. Why is verifying your environment important?
5. What does a successful Playwright test indicate?

---

# 🤖 AI Tutor Prompts

Use these in Skila/TestAmplify AI:

* “Why do I need to verify Node.js, npm, and Playwright?”
* “What does it mean if Playwright does not run?”
* “Explain the purpose of `npx playwright test`.”
* “How do I confirm that VS Code is configured correctly?”

---

# 💡 Lightbulb Reflection

Answer:

**Which tool (Node, npm, VS Code, Playwright) felt easiest to verify, and which felt hardest? Why?**

---

# 🎯 Interview Prep

Practice answering:

**“What steps do you take to verify a new automation environment?”**

Keep it concise and clear.

---