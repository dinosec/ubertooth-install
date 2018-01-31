# ubertooth-install
Ubertooth installation script for Kali Linux 2.x.

This script requires Internet access and will donwload multiple software packages to the current directory.

*IMPORTANT*: This script has not been updated, and will not be updated in the future, as the current Kali Linux Rolling version (e.g. 2017.3), already has the latest Ubertooth & libbtbb packages (e.g. 2017-03-R2). Ubertooth tools packet captures work by default with the latest Wireshark versions (see Ubertooth 2017-03-R2 release notes). Us the latest Kali Linux version

# Version:
2015-10-R1

# Tools Versions:
- Ubertooth & libbtbb: 2015-10-R1
- Kali Linux: 2.0.0
- Wireshark: 1.12.6
- Kismet: 2013-03-R1b

# Main Projects:
- [Ubertooth](https://github.com/greatscottgadgets/ubertooth/): 2015-10-R1
- [libbtbb](https://github.com/greatscottgadgets/libbtbb/): 2015-10-R1

# Usage:
```
From Git:
$ git clone https://github.com/dinosec/ubertooth-install.git
$ cd ubertooth-install

(or)

From the latest release: (using curl or wget)
$ curl -LOJ https://github.com/dinosec/ubertooth-install/archive/2015-10-R1.tar.gz
(or)
$ wget --content-disposition https://github.com/dinosec/ubertooth-install/archive/2015-10-R1.tar.gz

$ tar xzf ubertooth-install-2015-10-R1.tar.gz
$ cd ubertooth-install-2015-10-R1

Go:
$ sudo ./ubertooth_install.sh
```

Feedback and issues with this script would be most welcome!

