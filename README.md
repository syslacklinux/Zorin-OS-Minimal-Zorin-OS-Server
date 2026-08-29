# Zorin OS Minimal/Zorin OS Server

Not affiliated with Zorin OS BTW

Zorin OS Minimal Is a lightweight version of Zorin OS without graphical environment and its lighter than Zorin OS Lite

Zorin OS Server brings economic and technical scalability to your enterprise data center, public or private cloud. Whether you want to deploy an OpenStack cloud, a Kubernetes cluster, or a 50,000-node render farm, Zorin OS Server delivers the best value scale-out performance available.

# To install Zorin OS Minimal

Download Zorin OS Core on the website https://zorin.com/os/download/

Flash iso from usb

secure boot must be disabled

boot to zorin os install

setup zorin os

after install zorin os Dont login to zorin os desktop

ctrl alt f3

login on tty3

run sudo apt update

run sudo systemctl stop gdm;sudo systemctl disable gdm

remove zorin os desktop
sudo apt purge zorin-os-desktop

Clean up leftover unused packages by running
sudo apt autoremove && sudo apt clean

Force Purge the Remaining Zorin Components
sudo apt purge zorin-appearance gdm3 gnome-shell-extension-zorin-desktop-icons

then sudo apt autoremove -y

ls /usr/share/xsessions/
if theres no zorin.desktop you can continue to reboot
if theres zorin.desktop run it by sudo rm /usr/share/xsessions/zorin.desktop

remove gnome software and flatpak by running sudo apt purge gnome-software flatpak

Remove snap

You May Stop The Services Of Snap
   sudo systemctl stop snapd
   sudo systemctl disable snapd

  Purge Snapd (Recommended)
  sudo apt purge snapd

  Clean Up Leftover Directories
  rm -rf ~/snap
  sudo rm -rf /var/snap /var/lib/snapd /var/cache/snapd

  Autoremove
  sudo apt autoremove

  System Updates: Zorin OS may reinstall Snapd during major upgrades. To prevent this, you can block Snapd from being reinstalled:
  sudo apt-mark hold snapd

sudo reboot

You can continue without gui or install other desktop environment or window manager you like

If you are installing Any Desktop Environment You Like
Change Desktop Background From Default to Wallpapers From Zorin OS that available on /usr/share/backgrounds by right click then change wallpaper then change Default to Wallpapers From Zorin OS that available on /usr/share/backgrounds

# To install Zorin OS Server

Download Zorin OS Core on the website https://zorin.com/os/download/

Flash iso from usb

secure boot must be disabled

boot to zorin os install

setup zorin os

after install zorin os Dont login to zorin os desktop

ctrl alt f3

login on tty3

run sudo apt update

run sudo systemctl stop gdm;sudo systemctl disable gdm

remove zorin os desktop
sudo apt purge zorin-os-desktop

Clean up leftover unused packages by running
sudo apt autoremove && sudo apt clean

Force Purge the Remaining Zorin Components
sudo apt purge zorin-appearance gdm3 gnome-shell-extension-zorin-desktop-icons

then sudo apt autoremove -y

ls /usr/share/xsessions/
if theres no zorin.desktop you can continue to reboot
if theres zorin.desktop run it by sudo rm /usr/share/xsessions/zorin.desktop

remove gnome software and flatpak by running sudo apt purge gnome-software flatpak

Remove snap

You May Stop The Services Of Snap
   sudo systemctl stop snapd
   sudo systemctl disable snapd

  Purge Snapd (Recommended)
  sudo apt purge snapd

  Clean Up Leftover Directories
  rm -rf ~/snap
  sudo rm -rf /var/snap /var/lib/snapd /var/cache/snapd

  Autoremove
  sudo apt autoremove

  System Updates: Zorin OS may reinstall Snapd during major upgrades. To prevent this, you can block Snapd from being reinstalled:
  sudo apt-mark hold snapd

sudo reboot

Then install any server apps like apache or similar

If you Prefer with GUI

Login to zorin os desktop
Then install any server apps like apache or similar
