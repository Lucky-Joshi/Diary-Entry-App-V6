# 🚀 Diary App V6 – Ultimate Edition

Welcome to the final full-featured version of the Diary App. This edition combines all previous improvements and adds restore-from-trash, rich formatting, themes, and file export.

---

## 🔥 Core Features
- Rich Text Formatting: Bold, Italic, Underline
- Save as PDF & TXT
- Open last entry
- Light/Dark mode toggle
- Entries shown in 4-column grid
- Trash with ♻️ Restore
- Mood-based background (optional extension)
- Responsive, mobile-friendly design

---

## 🧠 Data Model (localStorage)
- `diaryEntries`: active entries (`[{id, html, date}]`)
- `diaryTrash`: deleted entries
- `diarySettings`: theme, future config

---

## 🧰 Tech Stack
- HTML5
- Tailwind CSS
- JavaScript (Vanilla + Blob + DOM APIs)

---

## 💾 Save Options
- **PDF**: Save current content as `.pdf`
- **TXT**: Save current content as `.txt`
- **Local AutoSave**: Browser stores your entries persistently

---

## 📦 UI Flow
1. Editor at top with formatting toolbar
2. Top ribbon: New, Open, Save
3. Entries grid below
4. Trash grid with Restore button

---

## ✅ Coming Soon (Optional Ideas)
- AI sentiment detection (happy, sad, etc.)
- Entry tagging and filters
- Progressive Web App (PWA) support

---

## 📢 Usage
1. Open `index.html` in browser.
2. Write your entry and use formatting as needed.
3. Click Save to store or export as PDF/TXT.
4. View previous entries below or restore from trash.

> 🧠 All content is stored locally. Nothing is uploaded or tracked.
