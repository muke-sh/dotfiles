### dotfiles

This repository contains my dotfiles, which are configuration files starting with a dot (e.g., .bashrc, .vimrc, etc.).

### Installing Stow

```bash
sudo apt install stow
```

### Setting up

1. Clone the repo:
    ```bash
        git clone https://github.com/muke-sh/dotfiles.git
    ```
2. Change into the cloned folder:
    ```bash
        cd dotfiles
    ```
3. Use Stow to symlink the dotfiles to your home directory:
    ```bash
        stow .
    ```
