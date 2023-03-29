
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

> Scraper found **6198** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|504|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|504|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|504|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|32|✅|
|[proxyscan.io](https://www.proxyscan.io)|0|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1510|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|846|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2859|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|207.148.16.130|80|United States|Piscataway|Choopa|
|2|92.137.250.246|3128|France|Gex|France Telecom Orange|
|3|207.148.16.130|80|United States|Piscataway|Choopa|
|4|157.90.153.104|8888|Germany|Falkenstein|Hetzner Online GmbH|
|5|8.219.176.202|8080|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|6|94.131.114.69|3128|Israel|Tel Aviv|Stark Industries Solutions LTD|
|7|91.194.3.215|1080|Russia|Krasnoyarsk|"RealHost" Ltd|
|8|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|9|51.79.50.31|9300|Canada|Victoria|OVH SAS|
|10|140.238.247.9|8100|India|Mumbai|Oracle Corporation|
|11|202.65.192.252|80|Hong Kong|Kwun Tong|Diyixian.com Limited|
|12|40.119.236.22|80|Singapore|Singapore|Microsoft Corporation|
|13|138.201.132.168|8118|Germany|Falkenstein|Hetzner Online GmbH|
|14|94.131.114.69|3128|Israel|Tel Aviv|Stark Industries Solutions LTD|
|15|20.191.183.124|3129|Japan|Tokyo|Microsoft Corporation|
|16|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|17|20.69.79.158|8443|United States|Quincy|Microsoft Corporation|
|18|20.191.183.123|3129|Japan|Tokyo|Microsoft Corporation|
|19|103.109.209.28|6969|Indonesia|Antirogo|Politeknik Negeri Jember|
|20|172.104.81.10|8080|Japan|Tokyo|Akamai Technologies|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

