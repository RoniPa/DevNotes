Launch bar to bottom:
```bash
gsettings set com.canonical.Unity.Launcher launcher-position Bottom
```
Install Lxde
```bash
sudo apt-get autoremove --purge unity unity-common unity-services unity-lens-\* unity-scope-\* unity-webapps-\* gnome-control-center-unity hud libunity-core-6\* libunity-misc4 libunity-webapps\* appmenu-gtk appmenu-gtk3 appmenu-qt\* overlay-scrollbar\* activity-log-manager-control-center firefox-globalmenu thunderbird-globalmenu libufe-xidgetter0 xul-ext-unity xul-ext-webaccounts webaccounts-extension-common xul-ext-websites-integration gnome-control-center gnome-session
sudo rm /usr/lib/thunderbird-addons/extensions/messagingmenu@mozilla.com.xpi
sudo apt-get install lubuntu-desktop
```
