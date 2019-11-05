
# Visual Studio Code Tips and Tricks

Microsoft Ignite 2019

Chris Dias

---
## Warm Up
  * [Insiders Build](https://code.visualstudio.com/insiders/)

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
    * Default: `Seti` File Icons, change to Material
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
## Navigation

### Viewlet Navigation
  * `SHIFT+CMD+D` to focus debug
  * `SHIFT+CMD+E` to focus explorer
  * `SHIFT+CMD+F` to focus search
  * `SHIFT+CMD+X` to focus extensions
  * `SHIFT+CTRL+G` to focus SCC
    * why not `CMD`? That's bound to Find Previous, a common binding... how do we we know?  Keyboard Shortcuts!

---
#### Key Bindings
  * Record keys to find bound action, conflicts
  * Custom Bindings to commands, tasks
  * When clause to scope when a binding is active
  * [Keymap Extensions](https://marketplace.visualstudio.com/search?target=VSCode&category=Keymaps&sortBy=Installs)

---
### Workspace Navigation
  * `CMD+R` recent projects, files
  * `F1` or `CMD+Shift+P` Command Palette
    * `?` Help
    * `>` Commands
    * `CMD+P` Fuzzy file search
    * `@` Symbol view
  * `CMD+SHIFT+;` breadcrumbs 

---
### Editor Navigation
  * `CMD+n` to navigate editor groups
    * `CTRL+n` to navigate editors with group
  * `alt` + hover, click to split editors horiz/vert
  * `CMD+B` hide/unhide Sidebar
  * `CMD+K Z` to enter Zen Mode
    * `esc esc` to exit!


---
## Side, Activity Bars
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
## Settings
  * UI vs JSON
    * Natural Language Search
  * Workspace vs. User
  * [My Settings](https://gist.github.com/chrisdias/4fbc535ce1ab5387f6623e25df62de19)

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

## Editing Code
  * Multiple Cursors
    * `CMD+D` to add cursors to search results
    * `CMD+SHIFT+L` to add cursors on every search result
  
  * `CMD+Shift+Ctrl+Arrow` to expand/contract selection

  * Emmet
    * `!` to scaffold HTML page
    * Down: `div>ul>li*3>span.className`
    * Up: `Emmet: Wrap with Abbreviation`
 
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
## Debugging
  * Single File 
  * Auto Attach (start with node --inspect)
  * Log points (eliminate `console.log`)
  * `launch.json`
  * Compound debugging

---
## Remote Development
  * SSH
  * WSL
  * Containers
  * Cloud Environments

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
