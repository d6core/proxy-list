
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

> Scraper found **6100** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|429|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|429|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|429|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|32|✅|
|[proxyscan.io](https://www.proxyscan.io)|100|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1238|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|864|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2915|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|20.241.236.196|3128|United States|Boydton|Microsoft Corporation|
|2|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|3|40.119.236.22|80|Singapore|Singapore|Microsoft Corporation|
|4|5.78.70.161|8080|United States|Portland|Hetzner Online GmbH|
|5|210.186.107.228|8083|Malaysia|Johor Bahru|ADSL Streamyx Telekom Malaysia|
|6|5.78.70.161|8080|United States|Portland|Hetzner Online GmbH|
|7|20.241.236.196|3128|United States|Boydton|Microsoft Corporation|
|8|20.241.236.196|3128|United States|Boydton|Microsoft Corporation|
|9|102.165.4.52|8001|United States|Ashburn|Tier.Net Technologies LLC|
|10|14.207.19.49|8080|Thailand|Bang Lamung|Triple T Broadband Public Company Limited|
|11|61.28.233.217|3128|Vietnam|Ho Chi Minh City|Vinadata broadcast via vinagame AS Number|
|12|103.163.134.4|8181|Indonesia|Plataran|PROVITEL|
|13|172.105.42.20|3132|India|Mumbai|Akamai Technologies|
|14|45.136.58.22|8888|Kazakhstan|Oral|Megahost Kazakhstan TOO|
|15|45.173.231.195|999|Ecuador|Guayaquil|Eliana Vanessa Morocho Oña|
|16|183.221.242.111|8443|China|Mianyang|China Mobile|
|17|5.78.42.62|50001|United States|Portland|Hetzner Online GmbH|
|18|190.15.158.183|8080|Cuba|Havana|Empresa de Telecomunicaciones de Cuba, S.A.|
|19|51.159.115.233|3128|France|Paris|SCALEWAY|
|20|2.59.119.238|3128|Turkey|Istanbul|Talha Bogaz|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

