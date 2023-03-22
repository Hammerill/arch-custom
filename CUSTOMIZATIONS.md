# Customizations
1. `sh -c "$(wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"` (can run as root too)
2. `git clone https://aur.archlinux.org/yay.git && cd yay && makepkg -si`
3. `yay -S flat-remix flat-remix-gtk google-chrome`
4. `echo '\ninclude "/usr/share/nano/*.nanorc"\ninclude "/usr/share/nano/extra/*.nanorc"' | sudo tee -a /etc/nanorc`
5. `yay -S nano-syntax-highlighting && echo 'include "/usr/share/nano-syntax-highlighting/*.nanorc"' | sudo tee -a /etc/nanorc`
6. `echo "--force-dark-mode\n--enable-features=WebUIDarkMode" >> ~/.config/chrome-flags.conf`
7. `yay -S fbset && echo 'alias r="sudo fbset -g 1024 768 1024 768 32"' >> ~/.zshrc` (you can look up other resolutions by running `videoinfo` in GRUB,
and instead of this command, you can also set resolution in `/etc/default/grub` and after run `sudo grub-mkconfig -o /boot/grub/grub.cfg`)
8. `yay -S lftp && echo "alias cpv='lftp -e \"cd ux0:/Download; mput *.vpk;quit\" 192.168.\"\$vitaip\":1337'" >> ~/.zshrc`
