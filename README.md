# Hacker's Todo List

A sleek, terminal-inspired todo list application for hackers who prefer the command line aesthetic.

## ✨ Features

🖥️ **Terminal-Style Interface** - Authentic command line aesthetics with modern UX  
✅ **Smart Task Management** - Intuitive add, complete, edit, and delete operations  
💾 **Persistent Storage** - Auto-save with IndexedDB for reliability  
⌨️ **Keyboard-First Design** - Navigate and manage tasks without touching your mouse  
🎯 **Priority System** - Visual indicators for high, medium, and low priority tasks  
🏷️ **Flexible Tagging** - Organize with custom categories and filters  
🌙 **Theme Support** - Dark mode by default (because hackers don't like light themes)

## Installation 🚀 Quick Start

```bash
git clone https://github.com/yourusername/hackers-todo-list.git
cd hackers-todo-list
npm install
```

## Usage

### Starting the Application

```bash
npm start
```

### Basic Commands

- **Add Task**: Click the input field or press `Ctrl+N` to add a new task
- **Complete Task**: Click the checkbox next to any task to mark it as complete
- **Delete Task**: Click the trash icon to remove a task
- **Clear Completed**: Remove all completed tasks at once

### Task Syntax

Tasks support markdown-style syntax for enhanced functionality:

```
# High priority task
## Medium priority task
### Low priority task

[tag] Task with a category tag
```

## Configuration

Edit `config.json` to customize:

```json
{
  "theme": "dark",
  "autoSave": true,
  "notifications": true,
  "soundEffects": false
}
```

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl+N` | New task |
| `Ctrl+D` | Delete selected task |
| `Ctrl+E` | Edit selected task |
| `Ctrl+/` | Toggle help |
| `↑/↓` | Navigate tasks |
| `Space` | Toggle task completion |

## Tech Stack

- Frontend: HTML5, CSS3, JavaScript
- Storage: LocalStorage / IndexedDB
- Build: Webpack
- Testing: Jest

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Roadmap

- [ ] Dark/Light theme toggle
- [ ] Task due dates and reminders
- [ ] Recurring tasks
- [ ] Task search and filtering
- [ ] Export tasks to JSON/CSV
- [ ] Sync across devices
- [ ] Terminal CLI version
- [ ] Vim keybindings mode

## Support

For bugs and feature requests, please [open an issue](https://github.com/yourusername/hackers-todo-list/issues).

## Author

**Your Name**
- GitHub: [@CodewithBikram2025](https://github.com/CodewithBikram2025)
- Twitter: [@Bikramjit2028]([https://x.com/Bikramjit2028?])

## Acknowledgments

- Inspired by terminal emulators and hacker culture
- Icons from [Font Awesome](https://fontawesome.com)
- Monospace font: [Fira Code](https://github.com/tonsky/FiraCode)

---

*"The best way to predict the future is to invent it." - Alan Kay*

**Happy Hacking! 🚀**



