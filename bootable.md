# Bootable

Download the woeusb script:
```bash
wget https://github.com/WoeUSB/WoeUSB/releases/download/v5.2.4/woeusb-5.2.4.bash
```

Install dependant pacakages:
```bash
sudo apt install wimtools -y
```

Create bootable USB fron linux:
```bash
sudo ./woeusb-5.2.4.bash --device Win10_21H2_English_x64.iso /dev/sdb
```
