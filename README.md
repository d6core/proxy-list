
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

> Scraper found **7379** proxies at the latest update. Usable proxies are below.

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
|[proxyscan.io](https://www.proxyscan.io)|0|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1852|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1068|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|3176|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|158.51.121.230|8881|Canada|Montreal|GLOBALTELEHOST Corp.|
|2|172.104.199.189|8080|United States|Richardson|Akamai Technologies|
|3|5.78.50.231|8888|United States|Portland|Hetzner Online GmbH|
|4|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|5|13.75.216.118|3128|Australia|The Rocks|Microsoft Corporation|
|6|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|7|50.246.120.125|8080|United States|Pasadena|Comcast Cable Communications, LLC|
|8|172.104.199.189|8080|United States|Richardson|Akamai Technologies|
|9|203.150.128.244|8080|Thailand|Vadhana|Internet Thailand Company Ltd|
|10|170.2.210.201|80|United States|Portland|Daimler Trucks of North America LLC|
|11|198.57.27.6|8850|Canada|Toronto|GLOBALTELEHOST Corp.|
|12|172.106.16.60|3128|United States|Ashburn|Psychz Networks|
|13|115.144.100.124|10000|South Korea|Gangdong-gu|HAIonNet|
|14|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|15|172.106.16.60|3128|United States|Ashburn|Psychz Networks|
|16|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|17|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|18|212.252.66.209|8080|Turkey|Istanbul|Superonline Iletisim Hizmetleri A.S.|
|19|45.70.202.11|8089|Ecuador|Quito|Nedetel S.A.|
|20|190.214.52.226|53281|Ecuador|Guayaquil|Corporacion Nacional De Telecomunicaciones - CNT EP|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

