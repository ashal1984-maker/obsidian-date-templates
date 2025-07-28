# 🗓️ Obsidian Custom Date Template (Templater + Hotkey)

Add a stylish, large, pink-highlighted date to any Obsidian note with one keystroke, using the Templater community plugin.  
Designed for daily notes, journaling, and workflow automation—no coding skills required after setup!

---

## 📑 Table of Contents

- [Features](#features)
- [Quick Start](#quick-start)
- [Usage](#usage)
- [Example Output](#example-output)
- [Troubleshooting](#troubleshooting)
- [Obsidian Automation Note](#obsidian-automation-note)
- [Inspiration](#inspiration)

---

## ✨ Features

- Eye-catching, pink-highlighted, human-readable date and time
- One-click or hotkey insertion anywhere in your notes
- Easy to customize (change color, format, etc.)
- Expandable: add more workflow-boosting templates as your needs grow

---

## 🚀 Quick Start

### 1. Install & Enable Templater Plugin

- Go to `Settings → Community Plugins → Browse`, search “Templater”.
- Click **Install** and **Enable**.

### 2. Create a `Templates` Folder

- In your vault, right-click in the File Explorer and choose **New folder**.
- Name it `Templates`.

### 3. Set Template Folder Location

- Go to `Settings → Templater`.
- Set `Template folder location` to `Templates`.

### 4. Add the Custom Date Template

- In the Templates folder, right-click and select **New note**.
- Name it: `custom-date`.

- Paste this (do **not** use a code block):

  ```markdown
  <span style="font-size: 20px; font-style: italic; background: #ffd1e9; padding: 3px 8px; border-radius: 4px;">
    <% tp.date.now("dddd, MMMM Do YYYY, h:mm:ss a") %>
  </span>
  
### 5. Assign a Hotkey for Fast Insertion

- Go to Settings → Hotkeys.
- Search for: Templater: Open insert template modal.

Assign your preferred hotkey (e.g., Cmd + Shift + E).

### 💡 Usage

- In any note, place your cursor where you want the date.
- Press your assigned hotkey (e.g., Cmd + Shift + E).
-Select custom-date from the modal.

Your beautiful, large, pink-highlighted date appears!

#### Tip:
You can tweak the <span> style or the date format string (tp.date.now(...)) to fit your preferences.

### 📋 Example Output

<span style="font-size: 20px; font-style: italic; background: #ffd1e9; padding: 3px 8px; border-radius: 4px;">
  Monday, July 29th 2025, 10:45:32 am
</span>

### 🛠️ Troubleshooting

- If you get a “not configured” error, ensure your Templates folder is set correctly in Templater settings.
- Do not paste the template code into a code block.
- If your hotkey conflicts, use a different combination in Hotkeys.

### 🌱 Obsidian Automation Note

This repository is for all who want to supercharge their note-taking, one workflow at a time.
Feel free to fork, adapt, or add your own snippets. If you invent a new workflow, open an issue or PR and share it with the community!

🔖 Inspiration
“Let routine work for you, so you can work on what matters.
Templates are the shortcuts to your future breakthroughs.”

### More workflow recipes coming soon!
---
