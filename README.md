# Configuration

1. Add variable to .zshrc or .bashrc

`export XDG_CONFIG_HOME = "$HOME/.config"`

2. Reload .zshrc or .bashrc

`source ~/.zshrc`

3. Clone repository in nvim folder

`cd $HOME/.config/nvim/lua`
`git clone https://github.com/chpenaf/astronvim-config.git`

4. Rename repository to 'user'

`mv astronvim-config user`

5. Run

`nvim  --headless -c 'autocmd User PackerComplete quitall' -c 'PackerSync'`

6. Done!
