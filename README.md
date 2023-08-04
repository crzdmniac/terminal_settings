# Terminal configs
Nothing fancy here, just hacking together some ansible to configure the terminal how I like it. This is Oh my Zsh with a powerlevel10k theme, and a few other apps. The theme can be reconfigured by typing `p10k configure` . Nerd fonts are required  as well; more info can be found in the powerlevel10k repo: [romkatv/powerlevel10k: A Zsh theme (github.com)](https://github.com/romkatv/powerlevel10k)

To get up and running quickly, all that should be required is the following command (in a Debian based OS).

`sudo apt update && sudo apt install ansible git -y && ansible-pull -U https://github.com/crzdmniac/terminal_settings.git -K`

If git and ansible are already installed, the first half of the line can be omitted. 