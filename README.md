# Playground
Ubuntu Server setup:
- [ ] Install server version (currently running 19.10)
  - VirtualBox management. After installation of server, network settings need to be changed from "NAT" to "Bridged" to allow, not only server access to the outside world but, access to the server from the outside world. This will allow virtual server to gain an IP address of the network (be sure to include SSHclient during installation of Linux).
- [ ] Pyenv installation/setup. Getting python environmennts configured correctly is more important than user feature preferences.
  - [Pyenv-installer](https://github.com/pyenv/pyenv-installer)
  - [Pyenv](https://github.com/pyenv/pyenv)
- [ ] pip.conf setup
  - Most packages used for development/automation will be downloaded from the Adtran pypi server.
  - [Adtran pypi server](https://artifactory.adtran.com/artifactory/api/pypi/pypi/simple)
```
[global]
index-url = https://artifactory.adtran.com/artifactory/api/pypi/pypi/simple
```
- [ ] SSH key generation (no passcode).
- [ ] Added some Adtran developement tools.
  - Photon-testbed-setup    (pip3)
  - Photon-testbed-vulture  (pip3)
  - Automatic-carnival      (pip3)
  - 
- [ ] Organize Github directories (git should have been installed with pyenv).
  - Tests
  - Tools
  - Topologies
- [ ] User preferences.
  - .bashrc add-ons.
  - Vim settings/plug-ins.



Erick Laitinen,
Product Qualification,
ADTRAN, Inc.,
901 Explorer Blvd.,
Huntsville, AL 35806
