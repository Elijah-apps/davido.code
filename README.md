```markdown
# 🤖 Davido – VS Code Coding Agent

> *“Code like a pro, vibe like a legend.”*  
> Inspired by the clean UI of **KiloCode** and the intelligent automation of **Zoo Code**.

---

## 🧠 About Davido

**Davido** is a powerful AI-powered coding agent designed to sit inside Visual Studio Code. It combines the minimalist, keyboard-first interface of KiloCode with the smart, context-aware assistance of Zoo Code. Whether you’re debugging, refactoring, or building from scratch, Davido is your silent co-pilot.

---

## ✨ Features

### 🧩 KiloCode-inspired Design
- Minimalist UI with a focus on **keyboard shortcuts**
- Clean command palette with fuzzy search
- Distraction-free coding environment
- Fast, lightweight, and responsive

### 🐾 Zoo Code-like Intelligence
- **Context-aware code completion**
- Auto-suggest fixes for bugs and linting errors
- Smart refactoring with one-click apply
- Natural language to code (comments → implementation)

### 🛠️ Davido Specifics
- `/ask` – Chat with Davido about your code
- `/fix` – Auto-generate a fix for the current error
- `/explain` – Get a plain-English breakdown of any function
- `/test` – Generate unit tests for the selected block
- `/doc` – Auto-generate JSDoc or Python docstrings

---

## 🚀 Getting Started

### Installation

1. Open VS Code
2. Go to Extensions (`Ctrl+Shift+X`)
3. Search for **"Davido"**
4. Click **Install**

### Activation

- Press `Ctrl+Shift+P` and type `> Davido: Start`
- Or use the shortcut: `Ctrl+Shift+D`

---

## 🧰 Commands

| Command          | Description |
|------------------|-------------|
| `> Davido: Ask`  | Open chat with Davido |
| `> Davido: Fix`  | Suggest a fix for the current error |
| `> Davido: Explain` | Explain selected code |
| `> Davido: Test` | Generate unit tests |
| `> Davido: Doc`  | Add documentation comments |

---

## 🎨 UI Preview

```
+--------------------------------------------------+
|  🔍 [Ask Davido...]                     [⚙️] [✕]  |
+--------------------------------------------------+
|  📁 Explorer                                      |
|  ├── src/                                         |
|  │   ├── main.js                                  |
|  │   └── utils.js                                 |
|  └── README.md                                    |
+--------------------------------------------------+
|  [Editor]                                         |
|                                                   |
|  function greet(name) {                           |
|    return `Hello, ${name}!`;                      |
|  }                                               |
|                                                   |
|  🤖 Davido: Try adding a default name parameter.  |
|                                                   |
+--------------------------------------------------+
|  [Terminal]  [Problems]  [Output]                 |
+--------------------------------------------------+
```

---

## 🔧 Configuration

You can customize Davido in your VS Code `settings.json`:

```json
{
  "davido.theme": "dark",
  "davido.suggestOnType": true,
  "davido.language": "en",
  "davido.autoFix": false
}
```

---

## 📦 Requirements

- VS Code v1.80+
- Node.js v18+ (for local LLM support)
- Internet connection (for cloud AI mode)

---

## 🤝 Contributing

We welcome contributions!  
Feel free to open issues or PRs on the [GitHub repo](https://github.com/yourusername/davido).

---

## 📄 License

MIT © 2026 Davido Labs

---

## ⭐ Support

If you like Davido, give us a ⭐ on GitHub and share it with your dev friends!

---

> Built with ❤️ for developers who love speed, simplicity, and intelligence.
```
