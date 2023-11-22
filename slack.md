# Install

`sudo apt install flatpak -y`

`sudo flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo`

`reboot`

`flatpak install flathub com.slack.Slack -y`

or

`sudo snap install snapd`

`sudo snap install core`

`sudo snap install slack`

## Uninstall

`flatpak uninstall --delete-data flathub com.slack.Slack`

`flatpak remove --unused`

or

`sudo snap remove slack`
