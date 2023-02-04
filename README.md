# Bash|Xray-Script

* UPDATE 21/05/2021 - added xray-nodomain script (see usage and installation below)





------------------------------------------
## :book: Installation - Without DNS

1)apt-get update -y && apt-get upgrade -y

2)sudo reboot 

4)sudo git clone https://github.com/MAFiA-6iXTY9iNE/bash-xray-script

5)cd bash-xray-script

6)sudo chmod +x xray-websocket.sh
6)sudo chmod +x vless+vmess.sh

7)sudo ./xray-websocket.sh

------------------------------------------



## :book: Unistallation (Remove xray-core and all modified config files from the server) *will not remove BBR

1) sudo rm  -rf  ~/bash-xray-script

2) sudo git clone https://github.com/MAFiA-6iXTY9iNE/bash-xray-script

3) cd bash-xray-script

4) sudo chmod 777 remove-xray.sh

5) sudo ./remove-xray.sh


