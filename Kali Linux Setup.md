# My steps for setting up a pen testing environment. 

Download latest from https://www.offensive-security.com/kali-linux-vm-vmware-virtualbox-image-download/ 

Install hotwax to fix tools that are broken and add some new ones. 
```
apt update -y
apt install -y git ansible
```
```
cd ~
git clone https://github.com/BrashEndeavours/hotwax.git
```
```
cd hotwax
ansible-playbook playbook.yml
```

This will fix tools that don't work like enum4Linux etc. Full list https://github.com/BrashEndeavours/hotwax.git

Next I install terminator for setting up split windowed consoles.

```
apt-get install terminator
```
