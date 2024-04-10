# vscode-ext-InTouch Readme

VSCode Formatter extension for InTouch is an open-source VSCode (**not official**).

It provides:

- Syntax Highlighting
- Snippets

## Installation

- Install from Github:

  - Copy or clone all into

    ```powershell
    cd ~\.vscode\extensions
    git clone "https://github.com/bforbenny/vscode-ext-InTouch.git"
    npm i

    # Restart vs-code after installation, to apply new settings
    ```

- Install from `VSIX`
  - Download releases from github page
  - From VSCode, open `extensions` or `Ctrl+Shift+X`
  - Click on `...` or `More actions`
  - Choose `Install from VSIX...`

## Compiling

```powershell
# Make sure node is installed
node -v

# Install vcse
npm install -g @vscode/vcse

# Check if VCSE is installed
npm list -g --depth=0

# Build VSIX
~\AppData\Romaing\npm\vcse package
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

## Credits

- https://github.com/vitalyruhl/intouch-language
