# adb-starter

adb-starter is a small systemd unit to start ADB as the root user in order to prevent permissions errors.

## adb server on pi

sudo apt-get install android-tools-adb android-tools-fastboot

## Service Installation

To install, copy `adb-starter.service` to `/etc/systemd/system`, then run `systemctl enable adb-starter.service` as root.
sudo chmod +x adb-starter.service
