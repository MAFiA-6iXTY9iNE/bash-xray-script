# Bash|Xray-Script

* UPDATE 21/05/2021 - added xray-nodomain script (see usage and installation below)





Xray-Script එක Use කරල ඔයාට High speed Network Connection එකක් / Low ping / Full stable Connection එකක් අත්විදින්න පුලුවන් ...


Manage Script

## :heavy_exclamation_mark: Requirements

* Ubuntu 20.04 or Ubuntu-latest Os එක සහිත Vps එකක්.
* UUID එකක් (V2rayN මගින් හෝ http://uuidgenerator.net මගින් UUID එකක් Genarate කරගන්න).
* DNS use නොකර Ip එකෙන් direct connect කරගන්න xray-nodomain ස්ක්‍රිප්ට් එක භාවිතා කරන්න.

------------------------------------------
## :book: Installation - Without DNS

1)apt-get update -y && apt-get upgrade -y

2)sudo reboot (update එකෙන් පසු restart කිරීමට)

4)sudo git clone https://github.com/MAFIAHEAVEN/bash-xray-script

5)cd bash-xray-script

6)sudo chmod +x xray-websocket.sh

7)sudo ./xray-websocket.sh

------------------------------------------



## :book: Unistallation (Remove xray-core and all modified config files from the server) *will not remove BBR

1) sudo rm  -rf  ~/bash-xray-script

2) sudo git clone https://github.com/MAFIAHEAVEN

3) cd bash-xray-script

4) sudo chmod 777 remove-xray.sh

5) sudo ./remove-xray.sh

