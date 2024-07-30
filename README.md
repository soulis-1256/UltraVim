This is my custom neovim config, based on [kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim).

# Linux Installation
```bash
rm -rf ~/.config/nvim
rm -rf ~/.local/share/nvim
```
```bash
git clone https://github.com/soulis-1256/UltraVim.git ~/.config/nvim --depth 1 && nvim
```

# Windows Installation
> [!NOTE]\
> You can find the correct path using `:echo stdpath('config')` inside neovim
```Powershell
Remove-Item -Recurse -Force "$env:LOCALAPPDATA\nvim"
Remove-Item -Recurse -Force "$env:LOCALAPPDATA\nvim-data"
```
```Powershell
git clone https://github.com/soulis-1256/UltraVim.git "$env:LOCALAPPDATA\nvim" --depth 1
```
