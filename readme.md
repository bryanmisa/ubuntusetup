# Settings after installation

## Applying the monitor settings on the login screen
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
# Installing VMware Workstation Pro 17
**Pre Requisites**
``` bash
sudo apt install build-essential
```
``` bash
sudo sh VMware-Workstation-Full-16.2.4-20089737.x86_64-Linux.bundle
```
# Running Balena Etcher
## Installing Pre-requisites
``` bash
sudo apt install libfuse2
```
# Setting up Ubuntu for Flutter Development

## Installing flutter
``` bash
sudo snap install flutter --classic
```

``` bash
flutter doctor
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
