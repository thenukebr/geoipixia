#geoipixia
"  ____ _____ ___ ___ ____ _____  _____    _    "<br>
" / ___| ____/ _ \_ _|  _ \_ _\ \/ /_ _|  / \"   <br>
"| |  _|  _|| | | | || |_) | | \  / | |  / _ \ " <br>
"| |_| | |__| |_| | ||  __/| | /  \ | | / ___ \ "<br>
 "\____|_____\___/___|_|  |___/_/\_\___/_/   \_\"<br>

EN:Script to track a IP/Host geolocation
PT-BR:Script para caçar a geolocalização de um IP/Host

-h or --help:
  Call this help menu
  Chama esse menu de ajuda

-i or --ipaddr:
  Information about IP/Hostname,like 192.168.1.1
  Informação sobre um IP, como 192.168.1.1

-n or --nmap:
  Locate IP and make scan with nmap
  Localiza o IP e faz um scan com nmap

--nmap-download:
  Download nmap from: https://nmap.org/

How to use:
  ./ipcrawler -n google.com
  ./ipcrawler -i 192.168.1.1

*Os sites "geoiptool.com" e "ipaddress.com" são utilizados para trazer informações do IP/Hostname
**esse script requer 'tor' e 'curl' para funcionar
**this script require 'tor' and 'curl' to work
