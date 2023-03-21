# Customizations
1. `sh -c "$(wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"` (can run as root too)
2. `git clone https://aur.archlinux.org/yay.git && cd yay && makepkg -si`
3. `yay -S flat-remix flat-remix-gtk google-chrome`
4. `echo '\ninclude "/usr/share/nano/*.nanorc"\ninclude "/usr/share/nano/extra/*.nanorc"' | sudo tee -a /etc/nanorc`
5. `echo "--force-dark-mode\n--enable-features=WebUIDarkMode" >> ~/.config/chrome-flags.conf`
