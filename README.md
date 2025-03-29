# Lumon Terminal Theme for VS Code

```
 _      _    _ __  __  ___  _  _
| |    | |  | |  \/  |/ _ \| \| |
| |    | |  | | |\/| | | | | .` |
| |___ | |__| | |  | | |_| | |\  |
|_____(_)____/|_|  |_|\___/|_| \_|
                                 
```

A VS Code theme inspired by the Lumon Industries terminal from the TV show "Severance". Experience the retro-futuristic, institutional aesthetic of Lumon's computer systems while writing your code.

## Preview

![Lumon Terminal Dark Theme](https://placeholder-for-screenshot.png)
![Lumon Terminal Light Theme](https://placeholder-for-screenshot.png)

## Features

- **Dark Theme**: Deep blue background with cyan text reminiscent of the MDR terminal screens
- **Light Theme**: Inverted colors for daytime coding while maintaining the Lumon aesthetic
- **Syntax Highlighting**: Carefully chosen colors to maintain the show's aesthetic while ensuring readability
- **UI Elements**: Complete theming of VS Code interface elements

## Installation

### From VS Code Marketplace

1. Open VS Code
2. Go to Extensions (Ctrl+Shift+X / Cmd+Shift+X)
3. Search for "Lumon Terminal Theme"
4. Click Install

### Manual Installation

1. Download the latest `.vsix` file from the [releases page](https://github.com/yourusername/lumon-terminal-theme/releases)
2. Open VS Code
3. Go to Extensions (Ctrl+Shift+X / Cmd+Shift+X)
4. Click on the "..." (More Actions) button at the top
5. Select "Install from VSIX..."
6. Navigate to your downloaded `.vsix` file and select it

## Usage

1. Open VS Code
2. Press Ctrl+K Ctrl+T (Cmd+K Cmd+T on Mac) to open the theme selector
3. Choose either "Lumon Terminal Dark" or "Lumon Terminal Light"

## Building from Source

If you want to customize the theme or contribute:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/lumon-terminal-theme.git
   cd lumon-terminal-theme
   ```

2. Make your changes to the theme files in the `themes` directory

3. Package the extension:
   ```bash
   # Install vsce if you don't have it
   npm install -g @vscode/vsce
   
   # Package the extension
   vsce package
   ```

4. The packaged `.vsix` file will be created in the project directory

## Color Palette

The theme uses the following colors from Lumon's terminals:

- `#102E47` - Deep blue background
- `#0B5CB9` - Bright blue for keywords
- `#0689AD` - Teal for functions
- `#0A3E7A` - Medium blue for UI elements
- `#244B6C` - Slate blue for inactive elements
- `#B6FCFE` - Cyan for text
- `#3E696B` - Muted teal for comments

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests if you have ideas for improvements.

## Credit and Inspiration

This theme is inspired by the Apple TV+ show "Severance" and the fictional Lumon Industries' terminal interfaces. No copyright infringement is intended - this is a fan project created out of appreciation for the show's distinctive visual design.

## License

MIT License - see LICENSE file for details.

---

*"Please enjoy each theme equally."* - Lumon Industries
