# **Lesson 05 — Creating Your First Project Folder**

> Module: **01 — Installing Node.js and VS Code**
> Track: **Test Automation Engineer — Course 0 (Intro to Automation Testing)**

---

# 🎯 Lesson Objective

By the end of this lesson, you will clearly understand:

* How to create a project folder for automation testing
* How to open a folder in VS Code
* How to initialize a JavaScript/TypeScript project
* What a `package.json` file is
* How your automation projects will be organized

This is the first step in building real Playwright automation projects.

---

# 📝 Text Mode (Full Explanation)

### **Why Create a Project Folder?**

Automation projects need an organized place where:

* Test files live
* Dependencies are installed
* Reports are generated
* Configurations are stored

The **project folder** is the home of your entire automation suite.

---

### **Step 1 — Create Your Project Folder**

Create a new folder anywhere on your machine.

Examples:

**Mac:**

1. Open Finder
2. Create a folder named:
   `automation-project`

**Windows:**

1. Open File Explorer
2. Create a folder named:
   `automation-project`

You can choose any name, but keep it simple and professional.

---

### **Step 2 — Open the Folder in VS Code**

1. Open VS Code
2. Click **File → Open Folder**
3. Select your new folder
4. Click **Open**

Your folder is now open as a VS Code workspace.

---

### **Step 3 — Open the Integrated Terminal**

In VS Code:

* Press **Ctrl + `** (Windows/Linux)
* Press **Control + `** (Mac)

Or go to:

**View → Terminal**

This terminal will be used for all automation commands.

---

### **Step 4 — Initialize the Project**

Inside the terminal, run:

```
npm init -y
```

This command:

* Creates a `package.json` file
* Initializes a Node.js project
* Prepares your folder for installing dependencies like Playwright

You should now see a new file:

```
package.json
```

This file tracks the tools and dependencies your automation project will use.

---

### **Step 5 — Confirm the Project Structure**

You should now see:

```
automation-project/
│
└── package.json
```

This is your starter automation environment.

You will install Playwright in the next lesson.

---

# 🧪 Mini Code Challenge

Inside your project folder terminal:

Run:

```
npm init -y
```

Then verify:

* The terminal prints: `Wrote to ... package.json`
* A `package.json` file appears in your folder

---

# 📝 Assignment

Create a note titled:

**“My First Automation Project Folder”**

Include:

1. Your folder name
2. Confirmation that you opened it in VS Code
3. Confirmation that `npm init -y` created `package.json`
4. A screenshot of your VS Code workspace

Share your setup screenshot with the instructor or on Slack/Pumble.

---

# ❓ Quick Quiz

1. Why do we create a dedicated project folder?
2. What command initializes a Node.js project?
3. What file is created after running `npm init -y`?
4. How do you open the VS Code terminal?
5. What does the `package.json` file store?

---

# 🤖 AI Tutor Prompts

Use these inside Skila/TestAmplify AI:

* “Explain what `npm init -y` does in simple terms.”
* “What is a project folder and why do automation engineers need one?”
* “Explain the purpose of the `package.json` file.”
* “Why is folder organization important in automation projects?”

---

# 💡 Lightbulb Reflection

Take 1–2 minutes and answer:

**What part of setting up the folder and project structure made the most sense to you today?**

---

# 🎯 Interview Prep

Practice answering:

**“What is the purpose of the package.json file in a test automation project?”**

Keep your answer short and clear.

---

If this matches perfectly → say **“Lesson 06”** and I’ll generate:

### ✔ Lesson 06 — Installing Playwright via npm
