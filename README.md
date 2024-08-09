# Neovim Custom Configuration | PWShehen

This repository contains a custom configuration for Neovim, created by me.

## Installation

### Linux

1. **Install Neovim**

   ```bash
   curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim-linux64.tar.gz
   sudo rm -rf /opt/nvim
   sudo tar -C /opt -xzf nvim-linux64.tar.gz
   ```

   Then add this to your shell config (`~/.bashrc`, `~/.zshrc`, ...):

   ```
   export PATH="$PATH:/opt/nvim-linux64/bin"
   ```

2. Clone the Repository

   ```bash
   git clone https://github.com/pwshehan/nvim-config.git ~/.config/nvim
   ```

3. Install Packer

   ```bash
   git clone --depth 1 https://github.com/wbthomason/packer.nvim \
   ~/.local/share/nvim/site/pack/packer/start/packer.nvim
   ```

4. Install Plugins

   Open Neovim and run `:PackerSync`.

### Windows

2. Clone the Repository

   ```powershell
   git clone https://github.com/pwshehan/nvim-config.git $HOME\AppData\Local\nvim
   ```

3. Install Packer

   ```powershell
   git clone https://github.com/wbthomason/packer.nvim "$env:LOCALAPPDATA\nvim-data\site\pack\packer\start\packer.nvim"
   ```
