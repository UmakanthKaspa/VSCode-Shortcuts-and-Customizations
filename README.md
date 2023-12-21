# Visual Studio Code Shortcuts and Customizations


### Display Shortcuts
- **Ctrl + B**: Toggle sidebar visibility.
- **Ctrl + Left Arrow**: Collapse all opened folders.
- **File Dragging**: Hold file and drag left to split screen or downwards.

### File Shortcuts
- **Ctrl + N**: Create a new file.
- **Ctrl + S**: Save the file.
- **Ctrl + O**: Open a file.
- **Ctrl + W**: Close the file.
- **Ctrl + Shift + T**: Reopen recently closed files.
- **Ctrl + Tab**: Switch between open files.

### VS Code Basics Shortcuts
- **Ctrl + C**: Copy the current line.
- **Ctrl + X**: Cut the current line.
- **Alt + Arrow Keys**: Move lines up or down.
- **Alt + Shift + Arrow**: Duplicate lines.
- **Ctrl + /**: Comment/uncomment a line.
- **Ctrl + [ or ]**: Indentation.

### Customizations Made
- **Enabled Auto Save**.
- **Moved Sidebar to the Right**.
- **Disabled Breadcrumbs and Minimap**.
- *Settings Used* (partial excerpt):
  ```{
    "tabnine.experimentalAutoImports": true,
    "workbench.sideBar.location": "right",
    "powermode.enabled": true,
    "files.autoSave": "afterDelay",
    "editor.fontSize": 18,
    "editor.fontFamily": "Input",
    "window.zoomLevel": 1,
    "workbench.iconTheme": "Monokai Pro Icons",
    "workbench.productIconTheme": "fluent-icons",
    "workbench.editor.empty.hint": "hidden",
    "breadcrumbs.enabled": false,
    "editor.minimap.enabled": false,
    "window.menuBarVisibility": "toggle",
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "workbench.colorTheme": "Monokai Pro",
    "editor.cursorBlinking": "expand"
  }
  ```

### Zinmode
- **Ctrl + K and Z**: Enter Zinmode to focus on the code. Press `Esc` twice to exit.

### Collapsing and Expanding Code
- **Ctrl + Shift + Left Arrow**: Collapse/Expand code.

### Terminal and Searching
- **Terminal Dragging**: Move terminal to different sides.
- **Ctrl + Shift + F**: Find and replace in VS Code.
- **Command Palette Usage**:
  - Find elements using `@`.
  - Jump to a line using `:no`.

### Navigation and Selection
- **Ctrl + Arrow Keys**: Navigate by word.
- **Home/End**: Go to start/end of lines or files.
- **Ctrl + Shift + Home/End**: Select content.

### Multi-Selection and Beautification
- **Alt + Click**: Multi-select.
- **Ctrl + L**: Select whole lines.
- **Shift + Alt + Arrow**: Multi-select by moving the cursor.
- **Enhance the Interface**:
  - Hide outlines, timeline, or activity bar if necessary.
  - Toggle the menu bar with `Alt` key.

### Extensions and Emmet
- **Extensions**: Explore Live Server and Prettier.
- **Emmet Usage**: Shortcuts for HTML and CSS.

### Sample Emmet Expressions
- Quick generation of HTML structures:
  ```
  div>(h1*3)
  <div>
     <h1></h1>
     <h1></h1>
     <h1></h1>
  </div>
  ```

---
