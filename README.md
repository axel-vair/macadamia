# Macadamia - Minimal Zsh Configuration

This is a minimal Zsh configuration aimed at users who want a clean, fast, and efficient setup without relying on frameworks like Oh My Zsh. It includes a simple Zsh theme and syntax highlighting using `zsh-syntax-highlighting`.

## Features

- **Minimal setup**: No need for large frameworks like Oh My Zsh. This configuration uses only essential plugins and a custom theme.
- **Syntax highlighting**: `zsh-syntax-highlighting` for improved readability of commands in the terminal.
- **Fast and lightweight**: No unnecessary dependencies or bloat, ensuring a fast and responsive terminal experience.
- **Easy to use**: Simply add the configuration to your setup and you're good to go.

## Requirements

- **Zsh**: Make sure you have Zsh installed on your system. Most Linux distributions come with it pre-installed, but if not, you can install it using your package manager.
- **Homebrew**: A package manager for macOS (or Linux). It's used here to install `zsh-syntax-highlighting` easily.
- **zsh-syntax-highlighting**: A plugin that adds syntax highlighting to Zsh.

## Theme (RobbyRussel like) 
<img width="743" alt="macadamia-theme" src="https://github.com/user-attachments/assets/819dce45-40e4-4728-92d7-ff4b118b4e8c" />


## Installation

#### Install Homebrew (if not installed already)

If you don't have Homebrew installed, you can install it with the following command:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

#### Install zsh-syntax-highlighting

Use homebrew to install zsh-syntax-highlighting. This is the only thing to install.
```bash
brew install zsh-syntax-highlighting
```

### Create `~/.zshrc` file


1. **Manual creation of the `~/.zshrc` file**: Since we are not using **Oh My Zsh** (or any similar framework), you need to manually create the `~/.zshrc` file and configure it yourself.
    ```bash 
    nano ~/.zshrc
    ```
2. **Add custom configurations**: Copy and paste macadamia_setup

3. **Relaod terminal**:
    ```bash
   source ~/.zshrc
   ``` 

With these changes, your installation guide is now better suited for a fully manual setup, without relying on heavy external tools like Oh My Zsh.


## Why This Configuration?

This configuration is designed for users who want a fast and minimal Zsh experience. By removing the overhead of frameworks like Oh My Zsh, you get a lean setup that focuses only on the features you need. It's perfect for those who want to keep their environment simple and efficient while still enjoying syntax highlighting and a clean prompt.

## Contributing

Feel free to open issues, suggest improvements, or submit pull requests. Contributions are welcome
