
# Visual Studio Code Tips and Tricks

Microsoft Ignite 2019

Chris Dias

---
## Warm Up
  * [Insiders Build](https://code.visualstudio.com/insiders/)
  * Command Palette `CMD+SHIFT+P` or `F1`

---
## Command Line
  * open current folder
    * `code .`
    * `code-insiders .`
  * `-w` to wait, lets you use as your git editor
    * `git config --global core.editor "code-insiders -w"`
  * `-d` to diff two files (example: `code -d file1.js file2.js`)
  * `-r` to reuse the same window (example: `code . -r`)
  * Need to install on Path (Mac)

---
## Themes
  * Two types: Icon and Environment
    * Icon
      * Default: `Seti` File Icons, change to Material
    * Color search...
  * Extension search query language
    * `@builtin` shows built in extensions
    * `@disabled`  shows disabled extensions
    * `@sort:installs ` sort by popularity
    * ...
  * Override Themes in Settings
    * `workspace.colorCustomizations: {}`
  * Create your own theme: `Developer Tools: Generate Color Theme from Current Settings`
    * `yo code`

---
## Settings
  * `CMD+,` to open settings
  * UI vs JSON
    * Natural Language Search
  * Workspace vs. User
  * [My Settings](https://gist.github.com/chrisdias/4fbc535ce1ab5387f6623e25df62de19)

---
## Navigation
* `F1` > `Toggle Screencast Mode`

### Workbench
  * `F1` or `CMD+Shift+P` Command Palette
    * `?` Help shows all you can do from palette
    * `view` switcher, even ones created by extensions
  * `CMD+B` hide/unhide Sidebar
  * `SHIFT+CMD+D` to focus debug
  * `SHIFT+CMD+E` to focus explorer
  * `SHIFT+CMD+F` to focus search
  * `SHIFT+CMD+X` to focus extensions
  * `SHIFT+CTRL+G` to focus SCC
    * Why not `CMD`? That's bound to Find Previous, a common binding... how do we we know?  Keyboard Shortcuts!

---
#### Key Bindings
  * Search for key combinations (record keys has a bug)
  * Create a custom binding, click on pencil
    * `CMD+S, C` to toggle Screencast mode
  * Toggle `json` view
    * `CMD+R` recent projects, files
    * When clause to scope when a binding is active
  * [Keymap Extensions](https://marketplace.visualstudio.com/search?target=VSCode&category=Keymaps&sortBy=Installs)

---
### Viewlets, Activity Bars
  * SideBar: Right Click, Move Left/Right
  * Explorer Viewlet
    * Open Editors
      * Control the number visible files in settings
      * Right click, Hide sashes
    * Add a file and a folder (e.g. type 'foo/bar/index.html`)
      * Works with `code ./foo/bar/index.html` too
    * Compare files
    * Gutter diffs (when backed by SCC)
  * Search
    * Right click, toggle location
  * Activity Bar
    * Hide/Show/Move Icons
  * Status Bar
    * Right click to hide extension contributions

---
### File Navigation
  * `CMD+P` Fuzzy file search
    * open to side vertically
    * `alt` to split horizontally
  * `CMD+n` to navigate editor _groups_
    * `CTRL+n` to navigate _editors_ with group
  * `@` Symbol view in a file
    * `@:` Symbol view by category
    * Related: `CMD+SHIFT+.` breadcrumbs 
    * Option Left, Right to move
  * `CMD+K Z` to enter Zen Mode
    * `esc esc` to exit!


---

## Editing Code
  * Multiple Cursors
    * `CMD+D` to add cursors to search results
    * `CMD+SHIFT+L` to add cursors on every search result
  
  * Emmet
    * `!` to scaffold HTML page
    * Down: `div>ul>li*3>span.className`
    * Up: `Emmet: Wrap with Abbreviation`
    * `CMD+Shift+Ctrl+Arrow` to expand/contract selection
 
  * HTML and CSS editing
    * Getting CSS/SCSS preview by mousing over the selector
    * CSS help (mozilla, accessibility)
    * ARIA help in `aria-` HTML tags
  
  * JavaScript
    * type checking with `@ts-check`
    * Refactorings
      * extract to function
      * extract to file

---
## Mastering the Terminal
* External terminal (`CMD+Shift+C`)
* Internal terminal (`CTRL+` `)
  * Default Shell (drop down)
  * Settings
* Good: Splitting 
  * Naming (`F1 term`)
* Better: `tmux`
  * `ctrl+b %` split vert
  * `ctrl+b q` pane numbers
  * `ctrl+b ->` `ctrl+b <-` move
  * Close VCode, reopen and reattach with 
  * `tmux ls` to list sessions, `tmux a` to attach
* cmatrix

---
## Debugging
  * Single File Debugging 
    * Start without debugging: `CTRL+F5`
  * Auto Attach (start with node --inspect)
  * Log points (eliminate `console.log`)
  * `launch.json`
  * Compound debugging

---
## Remote Development
  * Containers

---
## Extras

---
### Developer Tools
  * `F1` > `Developer`
  * `Toggle Screencast Mode`
  * `Reload Window`
  * `Reload with Extensions Disabled`
  * `Show running extensions`
  * `Set Log Level`
  * `Show Logs`

### Docker
  * [Docker Extension](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
  * Add files to workspace
  * `docker-compose`
  * Attach a shell
  * Debugging


---
# Happy Coding!
