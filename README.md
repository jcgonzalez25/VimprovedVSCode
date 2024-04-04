# VS Code Key Bindings README

This repos serves as a comprehensive guide to my custom key bindings configured in Visual Studio Code, covering both Vim extension settings and additional key bindings for project management, code editing, file exploration, terminal control, editor management, and debugging.

## Vim Extension Settings

### Navigation and Window Management
- **Next and Previous Editor Tab**
  - `<Space>tn`: Next editor tab.
  - `<Space>tN`: Previous editor tab.
- **Focus Editor Groups**
  - `<Space>fn`: Focus next editor group.
  - `<Space>fN`: Focus previous editor group.
- **Move Editor Between Groups**
  - `<Space>vif`: Move editor to first group.
  - `<Space>vil`: Move editor to last group.
  - `<Space>vin`: Move editor to next group.
  - `<Space>viN`: Move editor to previous group.

### File and Editor Management
- **Closing Editors**
  - `<Space>ceg`: Close editors in group.
  - `<Space>coe`: Close other editors.
  - `<Space>ceo`: Close editors in other groups.
- **File Operations**
  - `<Space>w`: Save file (`:w!`).
  - `<Space>q`: Close editor (`:q!`).
  - `<Space>x`: Save and close editor (`:x!`).

### Editor Splitting
- **Split Editor**
  - `<Space>sh`: Split editor left.
  - `<Space>sj`: Split editor down.
  - `<Space>sk`: Split editor up.
  - `<Space>sl`: Split editor right.

### Code Navigation and Operations
- **Problems and Markers**
  - `<Space>pn`: Go to next problem/marker.
  - `<Space>pN`: Go to previous problem/marker.
- **Rename and Quick Actions**
  - `<Space>r`: Rename symbol.
  - `<Space>a`: Quick fix actions.

### Miscellaneous
- **Other Commands**
  - `leader 1`, `leader 2`, `leader 3`: Focus on the first, second, and third editor group, respectively.

## Additional Key Bindings

### Project Management
- **List Git Projects in Sidebar**
  - `cmd+o`: Open list of Git projects in sidebar.

### Code Editing and Navigation
- **Expand and Contract Selection**
  - `ctrl+=`: Expand selection region.
  - `ctrl+-`: Contract selection region.
- **Multiple Selections**
  - `ctrl+n`: Add selection to next find match.
- **Quick Open Navigation**
  - `j`: Next item in Quick Open.
  - `k`: Previous item in Quick Open.

### File Explorer
- **Focus and Operations in File Explorer**
  - `ctrl+e`: Focus on File Explorer.
  - `a`: New file.
  - `r`: Rename file.
  - `c`: Copy file.
  - `p`: Paste file.
  - `d`: Delete file.

### Terminal Control
- **Terminal Navigation and Management**
  - `shift+space t n`: Next terminal.
  - `shift+space q`: Kill terminal.
  - `shift+space t shift+n`: Previous terminal.
  - `shift+j`: Toggle terminal.
  - `ctrl+\`: Toggle terminal when active.

### Editor Management
- **Split Editor**
  - `cmd+d`: Split editor.

### Save and Undo
- **Save and Zen Mode**
  - `cmd+s`: Save all files.
  - `cmd+z`: Toggle Zen Mode.

### Selection
- **Select All**
  - `cmd+a`: Select all content.

### Logging and Debugging
- **Turbo Console Log**
  - `cmd+i`: Display log message with Turbo Console Log.

This README provides an organized overview of your customized key bindings in VS Code, facilitating quick reference and understanding of each binding's function.
