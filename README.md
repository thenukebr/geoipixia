#Geoipixia

Idiomas:
  <a href="#ptbr">Português</a>
  <a href="#en">English</a>
<a href="#help">Ajuda/Help</a>

<a name="ptbr"></a>
  <i>Script para caçar a geolocalização de um IP/Host</i>
  
Script para retornar informações sobre um IP/Hostname utilizando as aplicações
web: "geoiptool.com" e "ipaddress.com". Com filtragem de dados via Shell Script
é retornado o maior número de informações sobre o IP/Hostname, também
podendo fazer um scan com nmap para retornar informações sobre o OS e portas
abertas.

-------------------------------------------------------------------------------------------------

<a name="en"></a>
  <i>Script to track a IP/Host geolocation</i>

Script to hunt the geolocation of an IP/Host Script to return informations about an IP/Hostname using the web applications:  "geoiptool.com" and "ipaddress.com". With filtering of data by way of Shell Script is returning more information about the IP/Hostname, also can do a scan with nmap to return informations about OS and open doors.

-------------------------------------------------------------------------------------------------

<a name="help"></a>
Help Menu - Menu de ajuda
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

<b>How to use:
  ./ipcrawler -n google.com
  ./ipcrawler -i 192.168.1.1
<b>

<i>
  -esse script requer 'tor' e 'curl' para funcionar
  -this script require 'tor' and 'curl' to work
</i>

<b>
Dependences:
  apt-get install php-curl tor torsocks
</b>

https://www.wildcardcorp.com/blog/tor-torify-torsocks
https://curl.haxx.se/
