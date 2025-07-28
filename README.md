# obsidian-date-templates
A collection of Obsidian Templater snippets for custom note-taking workflows. Includes a stylish, highlighted date template with step-by-step hotkey setup instructions.

# 🗓️ Obsidian Custom Date Template (Templater + Hotkey)

Add a stylish, large, pink-highlighted date to any Obsidian note with one keystroke, using the Templater community plugin.  
Designed for daily notes, journaling, and workflow automation—no coding skills required after setup!

---

## ✨ Features

- Eye-catching, pink-highlighted, human-readable date and time
- One-click or hotkey insertion anywhere in your notes
- Easy to customize (change color, format, etc.)
- Expandable: add more workflow-boosting templates as your needs grow

---

## 🚀 Quick Start

### 1. **Install & Enable Templater Plugin**

- Go to `Settings → Community Plugins → Browse`, search “Templater”.
- Click **Install** and **Enable**.

### 2. **Create a `Templates` Folder**

- In your vault, right-click in the File Explorer and choose **New folder**.
- Name it `Templates`.

### 3. **Set Template Folder Location**

- Go to `Settings → Templater`.
- Set `Template folder location` to `Templates`.

### 4. **Add the Custom Date Template**

- In the Templates folder, right-click and select **New note**.
- Name it: `custom-date`.

- Paste this (do **not** use a code block):

  ```markdown
  <span style="font-size: 20px; font-style: italic; background: #ffd1e9; padding: 3px 8px; border-radius: 4px;">
    <% tp.date.now("dddd, MMMM Do YYYY, h:mm:ss a") %>
  </span>
