# Zorin-OS-Minimal-Zorin-OS-Server

Not affiliated with Zorin OS BTW

To install Zorin OS Minimal

Download Zorin OS on the website https://zorin.com/os/download/

Flash iso from usb

secure boot must be disabled

boot to zorin os install

setup zorin os

after install zorin os Dont login to zorin os desktop

ctrl alt f3

login on tty3

run sudo apt update

run sudo systemctl stop gdm;sudo systemctl disbale gdm

remove zorin os desktop
sudo apt purge zorin-os-desktop

Clean up leftover unused packages by running
sudo apt autoremove && sudo apt clean

Force Purge the Remaining Zorin Components
sudo apt purge zorin-appearance gdm3 gnome-shell-extension-zorin-desktop-icons

ls /usr/share/xsessions/
if theres no zorin.desktop you can continue to reboot
if theres zorin.desktop run it by sudo rm /usr/share/xsessions/zorin.desktop

sudo reboot

To install Zorin OS Server

Download Zorin OS on the website https://zorin.com/os/download/

Flash iso from usb

secure boot must be disabled

boot to zorin os install

setup zorin os

after install zorin os Dont login to zorin os desktop

ctrl alt f3

login on tty3

run sudo apt update

run sudo systemctl stop gdm;sudo systemctl disbale gdm

remove zorin os desktop
sudo apt purge zorin-os-desktop

Clean up leftover unused packages by running
sudo apt autoremove && sudo apt clean

Force Purge the Remaining Zorin Components
sudo apt purge zorin-appearance gdm3 gnome-shell-extension-zorin-desktop-icons

ls /usr/share/xsessions/
if theres no zorin.desktop you can continue to reboot
if theres zorin.desktop run it by sudo rm /usr/share/xsessions/zorin.desktop

sudo reboot

Then install any server apps like apache or similar

If you Prefer with GUI

Login to zorin os desktop
Then install any server apps like apache or similar
