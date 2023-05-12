# Settings after installation
``` bash
sudo cp ~/.config/monitors.xml ~gdm/.config/monitors.xml
```
``` bash
sudo chown gdm:gdm ~gdm/.config/monitors.xml
```
# Install Cisco VPN OpenConnect on Gnome

``` bash
sudo apt-get install openconnect network-manager-openconnect-gnome
```

# Setting up Ubuntu for Flutter Development

## Installing flutter
``` bash
sudo snap install flutter --classic
```

## Installing Android Studio (Updated)
``` bash
sudo add-apt-repository ppa:maarten-fonville/android-studio
```

``` bash
sudo apt update
```

``` bash
sudo apt install android-studio -y
```

## Installing Hypervisor for Ubuntu
``` bash
sudo apt-get install qemu-kvm libvirt-daemon-system libvirt-clients bridge-utils
```
