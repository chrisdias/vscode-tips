
# Visual Studio Code Tips and Tricks

Microsoft Ignite 2019

Chris Dias


## Warm Up
  * Insiders Build
  
  * Command Line
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
  * `CMD+K 7` to enter Zen Mode
    * `esc esc` to exit!
  * `SHIFT+CMD+D` to focus debug
  * `SHIFT+CMD+E` to focus explorer
  * `SHIFT+CMD+F` to focus search
  * `SHIFT+CMD+X` to focus extensions
  * `SHIFT+CTRL+G` to focus SCC
    * why not `CMD`? That's bound to Find Previous, a common binding... how do we we know?  Keyboard Shortcuts!

  * Key Bindings
    * Keymap Extensions
    * Bindings
    * When clause

## Developer Tools
  * `F1` > `Developer`
  * `Toggle Screencast Mode`
  * `Reload Window`
  * `Reload with Extensions Disabled`
  * `Show running extensions`
  * `Set Log Level`
  * `Show Logs`

## Customizing the Environment
  
### Themes
  * Two types: Icon and Environment
    * Default: `Seti` File Icons, change to Material
  * Quick "Preview"
  * Extension search query language
    * Built-in Extensions
  * Override Themes in Settings
  * Create your own theme: `Developer Tools: Generate Color Theme from Current Settings`
    * `vsce`

### Side, Activity Bars
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
  

## Terminals
  * Fun with shell
  * External terminal (CMD+Shift+C)
  * splitting
  * renaming
  * run selected text in terminal
    * bind to key

## Editing Code
  * IntelliCode
  * Emmet
    * balance in/out (map to keyboard shortcut)
  * Formatting
    * Formatting Extensions
    * Format on Save, Paste, Type
  * JSON IntelliSense
    * package json packages
  * Multi-Cursors
    * CMD+D
  * Quick Fixes
  * Refactoring
  * Snippets
  * JS Type Checking
  * IntelliCode
  * Multiple Cursors
  * Add cursors to search results (CMD+D)
  * Add cursors on every search result (CMD+Shift+L)
  * Emmet (div>ul>li*3>span)
  * Selection expansion (CMD+Shift+Ctrl+Arrow)
  * collapsable reigons
  * refactor promises to async/await
  * type checking in js
  * auto imports (and configuring them)
  * full function to arrow function
  * extract method and other refactorings
  * ts-check



## Debugging
  * NodeJS
  * Single File
  * Launch.json
  * Compound 
  * Auto Attach (start with node --inspect)
  * Log points (eliminate console.log)
  * Column breakpoints, data breakpoints
  * C# debugging?
  * PS debugging?
  * pre/post launch tasks
  * debug receipes
  * client side browser debugging


## Docker
  * Extension
  * Add files to workspace
  * Debugging

## Cloud
  * App Service
  * Functions

## SCC
  * Built in support
  * GHPR
  * Actions

## Tasks
  * auto detect package.json
  * tasks.json
  * key bindings
  * debugging

## Remote Development
  * Local setup too hard
  * locked down box
  * SSH
  * WSL
  * Containers


## Extensions
  * Close All (Ben's)
  * Open/reopen Workbench (Mine)
  * GitLens
  * LiveShare

 
https://burkeholland.gitbook.io/vs-code-can-do-that/
 
My personal faves…
 
Move sidebar right. Do it. You know you want to.
Browser debugging. This is still the number 1 tip on vscodecandothat.com
Collapsible regions
Refactor promises to async/await
Using Emmet to Balance Inward/Outward and mapping that to a keyboard shortcut so it’s easier to select an entire element and all its contents
Soft Undo
Inline file and folder nesting (via simply changing the file/folder name)
Getting CSS/SCSS preview by mousing over the selector
Emmet’s Wrap individual lines
Emmet Update Image Size

docker debug, stream logs, ssh, etc
azure functions debug
prettier/eslint setup - people dig this. it's not easy to get it to work for everyone (conflicts with vscode settings too)
settings sync and settings.json (people like seeing settings they can grab)
shortcuts. people LOVE shortcuts
find references
Move to a new file / and how it changes import references
refactor require to import   



  


