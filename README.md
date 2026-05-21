# VS Code -> LazyVim Keybindings

## 1. Navigation & Definitions

| Action                | VS Code Shortcut | LazyVim Shortcut |
| --------------------- | ---------------- | ---------------- |
| Go to definition      | F12              | gd               |
| Peek definition       | Alt+F12          | gp               |
| Go back               | Alt+Left         | <C-o>            |
| Go forward            | Alt+Right        | <C-i>            |
| Go to type definition | Ctrl+F12         | gD               |
| Go to implementation  | Ctrl+F12         | gi               |
| Find references       | Shift+F12        | gr               |

---

## 2. Hover, Info & Diagnostics

| Action              | VS Code Shortcut | LazyVim Shortcut |
| ------------------- | ---------------- | ---------------- |
| Hover documentation | Ctrl+K Ctrl+I    | K                |
| Show diagnostics    | Panel / hover    | <leader>cd       |
| Next diagnostic     | F8               | ]d               |
| Prev diagnostic     | Shift+F8         | [d               |

---

## 3. Code Actions & Suggestions

| Action              | VS Code Shortcut | LazyVim Shortcut    |
| ------------------- | ---------------- | ------------------- |
| Code actions        | Ctrl+.           | <leader>ca          |
| Rename symbol       | F2               | <leader>cr          |
| Format document     | Shift+Alt+F      | <leader>cf          |
| Trigger suggestions | Ctrl+Space       | <C-Space>           |
| Signature help      | Ctrl+Shift+Space | <C-k> (insert mode) |

---

## 4. File Explorer & Search

| Action                  | VS Code Shortcut | LazyVim Shortcut    |
| ----------------------- | ---------------- | ------------------- |
| Toggle file explorer    | Ctrl+B           | <leader>e           |
| Find files              | Ctrl+P           | <leader>ff          |
| Search in project       | Ctrl+Shift+F     | <leader>fg          |
| Recent files            | Ctrl+R           | <leader>fr          |
| Rename file in explorer | F2               | r (inside Neo-tree) |

---

## 5. Tabs & Buffers

| Action          | VS Code Shortcut       | LazyVim Shortcut |
| --------------- | ---------------------- | ---------------- |
| Next tab        | Ctrl+Tab               | ]b               |
| Prev tab        | Ctrl+Shift+Tab         | [b               |
| Close tab       | Ctrl+W                 | <leader>bd       |
| Open tab picker | —                      | <leader>bb       |
| New tab         | Ctrl+N                 | :tabnew          |
| Switch tab      | Ctrl+PageDown / PageUp | gt / gT          |

---

## 6. Git

| Action    | VS Code Shortcut | LazyVim Shortcut |
| --------- | ---------------- | ---------------- |
| Git panel | Ctrl+Shift+G     | <leader>gs       |
| Git diff  | Built-in UI      | <leader>gd       |
| Git blame | —                | <leader>gb       |

---

## 7. Editing & Productivity

| Action                | VS Code Shortcut | LazyVim Shortcut |
| --------------------- | ---------------- | ---------------- |
| Toggle comment        | Ctrl+/           | gc               |
| Multi-cursor add next | Ctrl+D           | <C-n>            |
| Search & replace      | Ctrl+H           | :%s/old/new/g    |
| Open command palette  | Ctrl+Shift+P     | <leader><space>  |
