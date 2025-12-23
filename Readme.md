My dotfiles are very simple and can be used alongwith any linux distros, except if you want a reproducible setup resort to home-manager instead from the nix project !
Ideally in gentoo create a custom set in gentoo in /etc/portage/sets/sway-wm. Then to install use as root or elevated privileges   
$ # emerge -avqg @sway-wm

The portage specific options   
-a --ask ---> asks for y/n prompt to decide if you want to move with the default use flags   
-v --verbose ---> self explanatory   
-q --quiet ---> doesn't show the build process in the display   
-g --getbinpkg ---> fetches binaries if exists   
