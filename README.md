# VS Code -> LazyVim Keybindings

## 1. Navigation & Definitions

| Action                | VS Code Shortcut | LazyVim Shortcut |
| --------------------- | ---------------- | ---------------- |
| Go to definition      | F12              | gd               |
| Go back (after gd)    | Alt+Left         | CTRL-o           |
| Peek definition       | Alt+F12          | gp / gr          |
| Go forward            | Alt+Right        | CTRL-i           |
| Go to type definition | Ctrl+Shift+F12   | gy               |
| Go to implementation  | Ctrl+F12         | gI               |
| Find references       | Shift+F12        | gr / gR          |

---

## 2. Hover, Info & Diagnostics

| Action                | VS Code Shortcut | LazyVim Shortcut |
| --------------------- | ---------------- | ---------------- |
| Hover documentation   | Ctrl+K Ctrl+I    | K                |
| Show diagnostics      | Panel / hover    | leader-cx        |
| Next diagnostic/error | F8               | ]d               |
| Prev diagnostic/error | Shift+F8         | [d               |

---

## 3. Code Actions & Suggestions

| Action              | VS Code Shortcut | LazyVim Shortcut     |
| ------------------- | ---------------- | -------------------- |
| Code actions        | Ctrl+.           | leader-ca            |
| Rename symbol       | F2               | leader-cr            |
| Format document     | Shift+Alt+F      | leader-cf            |
| Trigger suggestions | Ctrl+Space       | CTRL-Space           |
| Signature help      | Ctrl+Shift+Space | CTRL-k (insert mode) |

---

## 4. File Explorer & Search

| Action               | VS Code Shortcut | LazyVim Shortcut |
| -------------------- | ---------------- | ---------------- |
| Toggle file explorer | Ctrl+B           | leader-e         |
| Find files           | Ctrl+P           | leader-ff        |
| Search in project    | Ctrl+Shift+F     | leader-sg        |
| Recent files         | Ctrl+R           | leader-fr        |
| New file             | Ctrl+N           | leader-fn        |
| Rename file          | F2               | a (in Neo-tree)  |

---

## 5. Tabs & Buffers

| Action             | VS Code Shortcut | LazyVim Shortcut |
| ------------------ | ---------------- | ---------------- |
| Next tab / buffer  | Ctrl+PgDown      | L or ]b          |
| Prev tab / buffer  | Ctrl+PgUp        | H or [b          |
| Close tab / buffer | Ctrl+W           | leader-bd        |

---

## 6. Terminals

| Action          | VS Code Shortcut | LazyVim Shortcut    |
| --------------- | ---------------- | ------------------- |
| Toggle terminal | Ctrl+`           | leader-ft or CTRL+/ |

---

## 7. Git Integration (LazyGit)

| Action          | VS Code Shortcut | LazyVim Shortcut |
| --------------- | ---------------- | ---------------- |
| Open Git UI     | Ctrl+Shift+G     | leader-gg        |
| View Git status | Ctrl+Shift+G     | leader-gs        |
| Close Git UI    | Escape / q       | q                |

---

## 8. Split Panes & Window Management

| Action                  | VS Code Shortcut | LazyVim Shortcut |
| ----------------------- | ---------------- | ---------------- |
| Split pane vertically   | Ctrl+\           | leader-w-        |
| Split pane horizontally | Ctrl+K Ctrl+\    | leader-w\|       |
| Focus left pane         | Ctrl+1 (or 2, 3) | CTRL-h           |
| Focus down pane         | Ctrl+1 (or 2, 3) | CTRL-j           |
| Focus up pane           | Ctrl+1 (or 2, 3) | CTRL-k           |
| Focus right pane        | Ctrl+1 (or 2, 3) | CTRL-l           |
| Close active pane       | Ctrl+W           | leader-wd        |
