# Custom VS Code Configuration 🎨🚀  

Welcome to Visual Studio Code configuration repository! This repo contains my personal `keybindings.json` and `settings.json` files, designed to make coding more efficient, visually appealing, and enjoyable. If you love customizing your development environment, you're in the right place. 😊  

---

## ✨ Features  

### 🖋 Editor Customizations  
- **Font:** [Lilex Nerd Font](https://www.nerdfonts.com/) for beautiful and developer-friendly visuals.  
- **Font Size & Weight:** Comfortable `20px` font size and `500` weight for better readability.  
- **Line Height:** Set to `2` for clean and spacious code lines.  
- **Minimap:** Disabled for a distraction-free coding experience.  
- **Smooth Scrolling:** Enabled for a buttery smooth experience while navigating.  

### 🎨 Workbench Enhancements  
- **Theme:** [Everforest Dark](https://marketplace.visualstudio.com/items?itemName=sainnhe.everforest) for a soothing dark interface.  
- **Icons:** [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) for intuitive file and folder icons.  
- **Activity Bar:** Positioned at the top for a cleaner workspace.  
- **Status Bar:** Hidden for minimal distractions.  

### 📁 File Explorer  
- **Drag-and-Drop:** Disabled confirmation for a faster workflow.  
- **Delete Confirmation:** Turned off to speed up operations.  

### 🗂 Git & Project Management  
- **Smart Commit:** Enabled for quick commits without staging.  
- **Auto-fetch:** Always keeps your git status updated.  
- **Project Manager:** Organizes projects by recency for better accessibility.  

### 🖥 Terminal Tweaks  
- **Font:** Lilex Nerd Font with `19px` size for consistency.  
- **Default Profile:** Set to Git Bash for Windows and Bash for macOS.  

### 🎻 Vim Mode Integration  
If you love Vim, this configuration includes:  
- **Leader Key:** Set to `<space>` for custom shortcuts.  
- **Easy Motion, Incremental Search, Clipboard Support:** Enabled for better Vim-like behavior.  
- **Custom Key Bindings:** A tailored set of bindings for both insert and normal modes.  

---

## 🎹 Keybindings Reference  

| Shortcut             | Command                                      | Description                                          |
|----------------------|----------------------------------------------|------------------------------------------------------|
| `Cmd+Q`             | `workbench.action.quit`                     | Quit VS Code.                                        |
| `Cmd+B`             | `workbench.action.toggleSidebarVisibility`  | Toggle sidebar visibility when not focused.         |
| `Cmd+B`             | `workbench.action.focusSideBar`             | Focus on the sidebar when already visible.          |
| `Cmd+L`             | `workbench.action.nextEditor`               | Navigate to the next editor tab.                    |
| `Cmd+H`             | `workbench.action.previousEditor`           | Navigate to the previous editor tab.                |
| `Cmd+S`             | `workbench.action.files.save`               | Save the current file.                              |
| `Cmd+W`             | `workbench.action.closeActiveEditor`        | Close the active editor tab.                        |
| `Cmd+F`             | `actions.find`                              | Search within the file.                             |
| `Cmd+Z`             | `undo`                                      | Undo the last action.                               |
| `Cmd+R`             | `redo`                                      | Redo the last undone action.                        |
| `Cmd+C`             | `editor.action.clipboardCopyAction`         | Copy the selected text.                             |
| `Cmd+X`             | `editor.action.clipboardCutAction`          | Cut the selected text.                              |
| `Cmd+V`             | `editor.action.clipboardPasteAction`        | Paste from the clipboard.                           |
| `J`                 | `list.focusDown`                            | Scroll down in the sidebar.                         |
| `K`                 | `list.focusUp`                              | Scroll up in the sidebar.                           |
| `Cmd+0`             | `workbench.files.action.focusFilesExplorer` | Focus on the file explorer.                         |
| `M M`               | `workbench.files.action.createFolderFromExplorer` | Create a new folder in the explorer.            |
| `A`                 | `workbench.files.action.createFileFromExplorer` | Create a new file in the explorer.               |
| `D`                 | `deleteFile`                                | Delete a file or folder in the explorer.            |
| `R`                 | `renameFile`                                | Rename a file or folder in the explorer.            |
| `Y`                 | `filesExplorer.copy`                        | Copy a file or folder from the explorer.            |
| `P`                 | `filesExplorer.paste`                       | Paste a file or folder in the explorer.             |
| `X`                 | `filesExplorer.cut`                         | Cut a file or folder from the explorer.             |
| `U`                 | `filesExplorer.cancelCut`                   | Cancel a file cut/copy action.                      |
| `Cmd+J`             | `workbench.action.terminal.focus`           | Focus on the terminal.                              |
| `Cmd+J`             | `workbench.action.focusActiveEditorGroup`   | Focus back to the editor from the terminal.         |
| `Cmd+Right`         | `workbench.action.terminal.resizePaneRight` | Resize the terminal pane to the right.              |
| `Cmd+Left`          | `workbench.action.terminal.resizePaneLeft`  | Resize the terminal pane to the left.               |
| `Cmd+Up`            | `workbench.action.terminal.resizePaneUp`    | Resize the terminal pane upward.                    |
| `Cmd+Down`          | `workbench.action.terminal.resizePaneDown`  | Resize the terminal pane downward.                  |
| `Cmd+N`             | `workbench.action.terminal.new`             | Open a new terminal.                                |
| `Cmd+/`             | `workbench.action.terminal.split`           | Split the terminal pane.                            |
| `Cmd+Backspace`     | `workbench.action.terminal.kill`            | Kill the current terminal.                          |
| `Cmd+L`             | `workbench.action.terminal.focusNext`       | Focus on the next terminal.                         |
| `Cmd+H`             | `workbench.action.terminal.focusPrevious`   | Focus on the previous terminal.                     |
| `Cmd+Shift+L`       | `editor.fold`                               | Collapse code blocks.                               |
| `Cmd+Shift+H`       | `editor.unfold`                             | Expand code blocks.                                 |
| `Cmd+D`             | `workbench.action.splitEditor`              | Split the editor window.                            |
| `Cmd+Right`         | `workbench.action.increaseViewSize`         | Increase the size of the file explorer view.        |
| `Cmd+Left`          | `workbench.action.decreaseViewSize`         | Decrease the size of the file explorer view.        |

**NOTE: This table offers a clear overview of your keybindings for quick reference! 🎉**
### How to Customize Keybindings?
1. Open `File > Preferences > Keyboard Shortcuts` or press `Ctrl+K, Ctrl+S`.  
2. Search for a command and edit its keybinding by clicking the pencil icon.  
3. Add new bindings in the `keybindings.json` file as needed.  

---

## 📦 How to Use  

### Clone this Repository  
```bash
https://github.com/coderboy-organization/vs-code-as-astrovim.git
```
## Apply the Configuration  

### Locate Your VS Code User Directory:  
1. Open Command Palette (`cmd+shift+p` or `ctrl+shift+p`).  
2. Type `Preferences: Open Settings (JSON)` and hit enter.  

### Replace Key Bindings and Settings:  
- Copy the contents of `keybindings.json` and `settings.json` from this repository into your corresponding VS Code files.  

### Install Recommended Extensions:  
- [Prettier - Code Formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)  
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)  
- [Everforest Theme](https://marketplace.visualstudio.com/items?itemName=sainnhe.everforest)  
- [Vim Extension](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)  

---

## 🛠 Recommended Extensions  

Here are some extensions that complement this configuration:  
- [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)  
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)  
- [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)  

---

## 🌟 Contribute  

If you have any suggestions or improvements, feel free to open an issue or submit a pull request.  

---

## 📃 License  

This repository is licensed under the [MIT License](./LICENSE).  

---

### How to Customize  

- Replace `your-username` and `your-repository-name` with your GitHub details.  
- Add or remove sections based on your preference.  

This README.md provides a clear, engaging, and easy-to-use introduction to your VS Code configuration repository! 🎉
