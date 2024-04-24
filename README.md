# Alacritty Configuration

This repository contains the configuration file for Alacritty, a fast and lightweight terminal emulator.

## Features

- Full-screen window with customizable dimensions and padding
- Startup mode set to "Maximized"
- Window decorations enabled
- Customizable font settings (Hack Nerd Font Mono)
- Customizable color scheme (based on the Tomorrow Night color palette)
- Clipboard integration for selected text
- Block-style cursor with unfocused hollow style
- Shell configuration using `/bin/bash` with login arguments

## Installation

1. Install Alacritty by following the official installation guide: [Alacritty Installation](https://github.com/alacritty/alacritty#installation)

2. Clone this repository or download the `alacritty.toml` file.

```bash
git clone https://github.com/yourusername/alacritty-config.git
```

3. Replace the default Alacritty configuration file with the one from this repository. The default location for the configuration file is:
   - Linux: `~/.config/alacritty/alacritty.yml`
   - macOS: `~/Library/Preferences/alacritty/alacritty.yml`
   - Windows: `%APPDATA%\alacritty\alacritty.yml`

4. Launch Alacritty, and it will use the provided configuration file.

## Customization

Feel free to customize the `alacritty.toml` file to suit your preferences. You can modify the following settings:

- Window dimensions, padding, and startup mode
- Font family, style, and size
- Color scheme (primary colors, cursor colors, normal colors, and bright colors)
- Selection behavior (saving to clipboard)
- Cursor style and unfocused hollow style
- Shell program and command-line arguments

For more information on available configuration options, refer to the [Alacritty Configuration Documentation](https://github.com/alacritty/alacritty/blob/master/alacritty.yml).

## Contributing

If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request. Contributions are always welcome!
