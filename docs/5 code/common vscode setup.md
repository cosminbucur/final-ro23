# autosave
File > Preferences > Commonly used Files:Autosave 
select `onFocusChange`

# disable minimap
File > Preferences Editor
Minimap:enabled
uncheck

# plugins

## visual
material icon theme
bracket pair colorizer 2
indent-rainbow *

## code
prettier
eslint
markdownlint *
auto rename tag
css peek
html css support

## tech
draw.io integration
plantuml
gitlens
todo tree

# console log shortcut

File > Preferences > Keyboard Shortcuts
Above the search bar on the right you'll see a icon that when you hover over says "Open Keyboard Shortcuts (JSON)", click on it
Add this to the JSON settings:

```json
{
  "key": "ctrl+shift+l",
  "command": "editor.action.insertSnippet",
  "when": "editorTextFocus",
  "args": {
    "snippet": "console.log('${TM_SELECTED_TEXT}$1')$2;"
  }
}
```
# exclude node modules
File > Preferences > Settings

files:exclude

node_modules/