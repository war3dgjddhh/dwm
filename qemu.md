# install
yay -S qemu-full
yay -S qemu-system-x86-64 virt-manager
systemctl status libvirtd
systemctl enable libvirtd --now
yay -S dnsmasq dmidecode
