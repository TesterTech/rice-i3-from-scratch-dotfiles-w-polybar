# rice-i3-from-scratch-dotfiles-w-polybar
***This repo is a work in progress***

## About
- This repo contains config folders for i3 and polybar. To use them copy them to your own computer (home dir) for example ```~/git/dotfiles``` and make symlinks to them using the ```ln -s``` command.

## Theme supplied
- The only theme I put in this repo is ***hack***, since I only use that one. The Original sources [ref1] had a buch of other themes. For me, I wanted to keep it as simple as possible so chose for just one theme.

## Fonts
The following two are needed for the polybar icons and text.
- "JetBrains Mono NL SemiBold" can install using dnf on Fedora (jetbrains-mono-nl-fonts)
- "Iosevka Nerd Font" you can get this from github user:ryanoasis
Copy to ~/.local/share/fonts and run ```sudo fc-cache -f -v``` to refresh the font cache.

## Optionals (may not need)
The following files and folders are put on this repo but may not need.. Will have to see when I make the clean install on Fedora 37.
~/.config/xfce4/xfconf
~/.config/xfce4/terminal
~/.config/qt5ct
~/.config/gtk-3.0/settings.ini


## References
- [ref1] Original sources are by 'Aditya Shakya @adi1090x' as you can see in the config files headers (https://github.com/adi1090x/polybar-themes).
- I got the files from 'Rosan Paudel's video (https://www.youtube.com/channel/UCGv-g37PzdwiJ2LkJChH-ug)' and made them fit for my system like you can see in the YT video on my channel https://www.youtube.com/@testertech
- Fedora i3 spin https://spins.fedoraproject.org/en/i3/
