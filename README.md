# vscode-ext-InTouch Readme

VSCode Formatter extension for InTouch is an open-source VSCode (**not official**), providing:

- Syntax Highlighting
- Code Folding
- Snippets

## Installation

### Install from Github

```powershell
cd ~\.vscode\extensions
git clone "https://github.com/bforbenny/vscode-ext-InTouch.git"
npm i

# Restart vs-code after installation, to apply new settings
```

### Install from `VSIX`

- Download [latest release](https://github.com/bforbenny/vscode-ext-InTouch/releases/latest)
- From VSCode, open `extensions` or `Ctrl+Shift+X`
- Click on `...` or `More actions`
- Choose `Install from VSIX...`

## Building

```powershell
# Make sure node is installed
node -v

# Install vsce
npm install -g @vscode/vsce

# Check if vsce is installed
npm list -g --depth=0

# Build VSIX
~\AppData\Roaming\npm\vsce package
```

## Snippets

| Snippet  | Description           |
| -------- | --------------------- |
| dimb#    | DIM BOOLEAN           |
| dimi#    | DIM INTEGER           |
| dims#    | DIM STRING            |
| if#      | if code block         |
| ife#     | if else code block    |
| for#     | for code block        |
| log#     | Log Message block     |
| comment# | add new comment block |

## How to Use

> Save your code as `.vi` or `.vbi` for automatic language recognition

> Change `plaintext` to `intouch` for manual language switching

> Type in any snippet and press enter

> Code folding is supported for `IF/ENDIF`, `WHILE/ENDWHILE`, and `FOR/NEXT` blocks

## Credits

- https://github.com/vitalyruhl/intouch-language
