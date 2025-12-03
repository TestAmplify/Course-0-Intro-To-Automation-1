# **Lesson 06 — Using VS Code Run and Debug**

> Module: **08 — Understanding VS Code Debugging Tools**

---

# 🎯 Lesson Objective

You will learn:

* How to run tests using the VS Code Debugger
* How launch configurations work
* How to debug using the sidebar

---

# 📝 Text Mode (Full Explanation)

### **Open the Run and Debug Panel**

Left sidebar → ▶️ **Run and Debug**

---

### **Run a Test in Debug Mode**

Choose:

* "Run Script"
* "Debug Playwright Test"
* Or create a `.vscode/launch.json` file

---

### **Example Launch Configuration**

```json
{
  "type": "node",
  "request": "launch",
  "name": "Debug Playwright Tests",
  "program": "${workspaceFolder}/node_modules/@playwright/test/cli.js",
  "args": ["test", "--headed"],
  "console": "integratedTerminal"
}
```

---

### **Why Use Run & Debug**

✔ Streamlined debugging
✔ Integrated stepping
✔ Easy to inspect values
✔ View breakpoints in UI

---

# 🧪 Mini Code Challenge

Run a test using VS Code’s debug mode.

---

# 📝 Assignment

Write:

**“How I Ran My First Test Using Run & Debug”**

---

# ❓ Quick Quiz

1. What does the Run & Debug panel do?
2. What file holds debugging configuration?
3. What does `--headed` do in debug mode?

---

# 🤖 AI Tutor Prompts

* “Explain how to run Playwright tests in VS Code debug mode.”

---

# 💡 Lightbulb Reflection

**Was debugging easier from VS Code or the CLI? Why?**

---

# 🎯 Interview Prep

**“How do you use VS Code to debug Playwright tests?”**

---