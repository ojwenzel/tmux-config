# Tmux Configuration

This repository contains a custom tmux configuration file. This configuration enhances the default tmux experience with additional key bindings, improved status bar, and various other tweaks to improve productivity.

## Installation

### Step 1: Clone the Repository

First, clone this repository to your local machine:

```sh
git clone https://github.com/yourusername/tmux-config.git
```

### Step 2: Copy the Configuration File

Copy the `tmux.conf` file to your home directory:

```sh
cp tmux-config/tmux.conf ~/.tmux.conf
```

### Step 3: Source the Configuration File

To apply the configuration changes, you need to source the configuration file. You can do this by running the following command in your terminal:

```sh
tmux source-file ~/.tmux.conf
```

Alternatively, you can restart your tmux session to automatically load the new configuration.

## What This Configuration Does

- **Custom Key Bindings**: Adds several custom key bindings for easier window and pane management.
- **Enhanced Status Bar**: Improves the status bar with additional information such as system stats, date, and time.
- **Mouse Support**: Enables mouse support for easier pane resizing and window switching.
- **Improved Copy Mode**: Enhances copy mode with vim-like key bindings for more efficient text selection and copying.
- **Performance Tweaks**: Includes various performance tweaks to make tmux run smoother and more efficiently.

Feel free to explore and modify the `tmux.conf` file to suit your personal preferences.
