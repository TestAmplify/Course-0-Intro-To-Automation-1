# **Lesson 06 — Installing Playwright via npm**

> Module: **01 — Installing Node.js and VS Code**

> Track: **Test Automation Engineer — Course 0 (Intro to Automation Testing)**

---

# 🎯 Lesson Objective

By the end of this lesson, you will clearly understand:

* What Playwright is and why we use it for automation testing
* How to install Playwright using npm
* What files Playwright generates for you
* What the Playwright Test Runner is
* How to confirm the installation was successful

This is the moment your environment becomes *automation-ready*.

---

# 📝 Text Mode (Full Explanation)

### **What Is Playwright?**

Playwright is a modern, fast, cross-browser automation framework built by Microsoft.

It allows you to automate:

* Chrome
* Firefox
* WebKit (Safari engine)

What makes Playwright powerful:

✔ Auto-waiting
✔ Smart locators
✔ Fast execution
✔ Parallel testing
✔ Built-in test runner
✔ Flake-resistant
✔ Great debugging tools

This course uses Playwright with **JavaScript/TypeScript**, the industry-standard stack for modern automation engineers.

---

### **Installing Playwright in Your Project**

Before installing Playwright, make sure:

* Node.js is installed
* You created your project folder
* You ran `npm init -y` to generate `package.json`

Now open the terminal **inside your project folder** and run:

```
npm init playwright@latest
```

You will see prompts asking:

* Do you want to install Playwright? → **Yes**
* Install browsers? → **Yes**
* Add GitHub actions workflow? → (optional, you can say **No** for now)

Playwright will then install:

* All required dependencies
* The test framework
* Browser binaries
* Recommended folder structure

---

### **What Playwright Creates for You**

After installation, your project will now contain:

```
playwright.config.js       # main configuration file
tests/                     # your test folder
  example.spec.js          # sample test
```

You also get the following commands:

* Run all tests
* Open the Playwright UI
* Generate reports

---

### **Verify Playwright Installation**

Run the following command:

```
npx playwright --version
```

You should see something like:

```
Version 1.43.x
```

Then try running the sample test:

```
npx playwright test
```

If the test runs (you’ll see a report), then Playwright is installed successfully.

---

### **Optional: Install Browsers Manually**

If needed, you can install browser binaries separately:

```
npx playwright install
```

This ensures:

* Chromium
* Firefox
* WebKit

are all available for testing.

---

# 🧪 Mini Code Challenge

Inside your project folder:

1. Run:

   ```
   npm init playwright@latest
   ```
2. Then run:

   ```
   npx playwright --version
   ```
3. Then run your first sample test:

   ```
   npx playwright test
   ```

If the test passes → ✔ You did it!

---

# 📝 Assignment

Create a note titled:

**“My Playwright Installation Confirmation”**

Include:

1. The Playwright version installed
2. A screenshot of running `npx playwright test`
3. Your `tests/example.spec.js` file if created automatically

Share it with your instructor or on Slack/Pumble.

---

# ❓ Quick Quiz

1. What is Playwright used for?
2. What command installs Playwright?
3. What folder does Playwright create for tests?
4. How do you check Playwright’s version?
5. Why is Playwright preferred for modern web automation?

---

# 🤖 AI Tutor Prompts

Use inside Skila/TestAmplify AI:

* “Explain Playwright in beginner-friendly terms.”
* “What is the difference between Playwright and Selenium?”
* “What does the Playwright install command do?”
* “How do I run my Playwright tests?”

---

# 💡 Lightbulb Reflection

Take 1–2 minutes and answer:

**What part of installing Playwright was the most exciting or surprising to you?**

---

# 🎯 Interview Prep

Practice answering:

**“Explain what Playwright is and why automation engineers use it.”**

Aim for 20–30 seconds.

---
