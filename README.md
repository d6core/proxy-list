
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)
[![zevtyardt - proxy-list](https://img.shields.io/static/v1?label=zevtyardt&message=proxy-list&color=blue&logo=github)](https://github.com/zevtyardt/proxy-list "Go to GitHub repo")
[![stars - proxy-list](https://img.shields.io/github/stars/zevtyardt/proxy-list?style=social)](https://github.com/zevtyardt/proxy-list)
[![forks - proxy-list](https://img.shields.io/github/forks/zevtyardt/proxy-list?style=social)](https://github.com/zevtyardt/proxy-list)
[![Proxy Updater](https://github.com/zevtyardt/proxy-list/workflows/Proxy%20Updater/badge.svg)](https://github.com/zevtyardt/proxy-list/actions?query=workflow:"Proxy+Updater")
![GitHub repo size](https://img.shields.io/github/repo-size/zevtyardt/proxy-list)
[![GitHub commit activity](https://img.shields.io/github/commit-activity/m/zevtyardt/proxy-list?logo=commits)](https://github.com/zevtyardt/proxy-list/commits/main)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.

> Scraper found **6005** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|302|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|302|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|302|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|0|🚫|
|[proxyscan.io](https://www.proxyscan.io)|0|🚫|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1133|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|638|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|3283|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|2|135.148.95.28|3128|United States|Reston|OVH SAS|
|3|5.39.105.211|3128|France|Lyon|OVH SAS|
|4|51.159.115.233|3128|France|Paris|SCALEWAY|
|5|200.125.168.154|999|Dominican Republic|Santiago de los Caballeros|WIRELESS MULTI SERVICE VARGAS CABRERA, S. R. L|
|6|45.8.179.242|1337|United Kingdom|London|HOSTLAND|
|7|167.249.29.220|999|Chile|Santiago|Grupo Metrowan Telecom SPA|
|8|147.139.173.19|3128|Indonesia|Jakarta|Alibaba.com LLC|
|9|185.39.50.2|1337|Germany|Blankenfelde|NETZNUTZ|
|10|109.194.101.128|3128|Russia|Yoshkar-Ola|CJSC "ER-Telecom Holding" Yoshkar-Ola branch|
|11|185.217.137.241|1337|Seychelles|Cascade|Stallion Network Services Limited|
|12|45.8.179.241|1337|United Kingdom|London|HOSTLAND|
|13|134.238.252.143|8080|India|Mumbai|Google LLC|
|14|185.217.137.216|1337|Seychelles|Cascade|Stallion Network Services Limited|
|15|51.195.19.222|3131|Germany|Limburg an der Lahn|OVH SAS|
|16|185.217.137.242|1337|Seychelles|Cascade|Stallion Network Services Limited|
|17|135.148.95.28|3128|United States|Reston|OVH SAS|
|18|159.89.132.108|8989|United States|Santa Clara|DigitalOcean, LLC|
|19|190.63.35.30|9812|Ecuador|Ambato|CONECEL|
|20|145.40.121.15|3128|Brazil|São Paulo|Packet Host, Inc.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

