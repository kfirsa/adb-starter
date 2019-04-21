# adb-starter

adb-starter is a small systemd unit to start ADB as the root user in order to prevent permissions errors.

## Installation

To install, copy `adb-starter.service` to `/etc/systemd/system`, then run `systemctl enable adb-starter.service` as root.
sudo chmod +x adb-starter.service
