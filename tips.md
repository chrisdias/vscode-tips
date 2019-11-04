
# Visual Studio Code Tips and Tricks

Microsoft Ignite 2019

Chris Dias


## Warm Up
  * Insiders Build

## Developer Tools
  * `F1` > `Developer`
  * `Toggle Screencast Mode`
  * `Reload Window`
  * `Reload with Extensions Disabled`
  * `Show running extensions`
  * `Set Log Level`
  * `Show Logs`

## Command Line
  * `code .`  (need to install on path)
  * `code-insiders .`   
  * `-r` to reuse the same window
  * `-d` to diff two files
  * `-w` lets you use as your git editor
    * `git config --global core.editor "code-insiders -w"`

## Navigation
  * `F1` or `CMD+Shift+P` Command Palette
    * `?` Help
    * `>` Commands
    * Fuzzy file search
    * `@` Symbol view
  * `CMD+SHIFT+;` breadcrumbs 
  * `CMD+R` recent projects, files
  * `CMD+B` hide/unhide Sidebar
  * `CMD+n` to navigate editor groups
  * `CTRL+n` to navigate editors 
  * `alt` + hover, click to split editors horiz/vert
  * `CMD+K Z` to enter Zen Mode
    * `esc esc` to exit!
  * `SHIFT+CMD+D` to focus debug
  * `SHIFT+CMD+E` to focus explorer
  * `SHIFT+CMD+F` to focus search
  * `SHIFT+CMD+X` to focus extensions
  * `SHIFT+CTRL+G` to focus SCC
    * why not `CMD`? That's bound to Find Previous, a common binding... how do we we know?  Keyboard Shortcuts!

## Key Bindings
  * Keymap Extensions
  * Bindings
  * When clause

## Themes
  * Two types: Icon and Environment
    * Default: `Seti` File Icons, change to Material
  * Quick "Preview"
  * Extension search query language
    * Built-in Extensions
  * Override Themes in Settings
  * Create your own theme: `Developer Tools: Generate Color Theme from Current Settings`
    * `vsce`

## Side, Activity Bars
  * Right Click, Move Left/Right
  * Explorer
    * Open Editors
      * Control the number in settings
      * Right click, Hide
    * Add a file and a folder (e.g. type 'foo/bar/index.html`)
      * Works with `code ./foo/bar/index.html` too
  * Search
    * Right click, toggle location
  * Activity Bar
    * Hide/Show/Move Icons
  * Status Bar
    * right click to hide extension contributions
  
## Settings
  * UI vs JSON
  * Workspace vs Global vs Remote
  * Auto Update
    * Extension auto update
    * Hide recommendations: showRecommendationsOnlyOnDemand
  * Font Ligatures
    * Fonts.txt
    * Cascadia Code
  * ToDo: What to go through?

## Terminals
* External terminal (`CMD+Shift+C`)
* Internal terminal (`CTRL+` `)
  * Default Shell (drop down)
  * Settings
* Good: Splitting 
  * Naming (`F1 term`)
* Better: `tmux`
  * `tmux a` attach
  * `ctrl+b %` split vert
  * `ctrl+b q` pane numbers
  * `ctrl+b ->` `ctrl+b <-` move
* cmatrix

## Editing Code
  * Warm up with Multiple Cursors
    * `CMD+D` to add cursors to search results
    * `CMD+SHIFT+L` to add cursors on every search result
  
  * `CMD+Shift+Ctrl+Arrow` to expand/contract selection

  * Completions
    * IntelliCode
    * JSON Completions
      * `package.json modules`

  * Emmet
    * `!` to scaffold HTML page
    * Down: `div>ul>li*3>span.className`
    * Up: Wrap with Abbreviation

  * Formatting
    * Formatting Extensions
      * Prettier 
    * svg -> xml formatter
    * Format on Save, Paste, Type
  
  * HTML and CSS editing
    * Getting CSS/SCSS preview by mousing over the selector
    * CSS help (mozilla, accessibility)
    * ARIA help in `aria-` HTML tags
  
  * JavaScript
    * type checking with `@ts-check`
    * Refactorings
      * extract to function
      * extract to file

  * SCC/Changes
    * Diff view of changes from gutter

## Debugging
  * Single File
  * Auto Attach (start with node --inspect)
  * Log points (eliminate `console.log`)
  * `launch.json`
  * Compound debugging

### Docker
  * Extension
  * Add files to workspace
  * Debugging

## Tasks
  * auto detect package.json
  * tasks.json
  * key bindings
  * debugging

## Remote Development
  * SSH
  * Containers

## Favorite Extensions
  * Close All (Ben's)
  * Open/reopen Workbench (Mine)


