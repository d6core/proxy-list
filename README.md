
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

> Scraper found **6275** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|241|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|241|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|241|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1727|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|943|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2622|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|210.172.199.88|8080|Japan|Gifu|KITAGATA|
|2|20.210.34.43|3129|Japan|Tokyo|Microsoft Corporation|
|3|20.69.79.158|8443|United States|Quincy|Microsoft Corporation|
|4|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|5|73.242.86.12|8118|United States|Minnetonka|Comcast Cable Communications|
|6|54.39.183.24|3128|Canada|Beauharnois|OVH SAS|
|7|134.209.107.145|8080|Singapore|Singapore|DigitalOcean, LLC|
|8|54.37.21.230|3128|France|Gravelines|OVH SAS|
|9|80.14.219.107|3128|France|Livry-Gargan|France Telecom|
|10|8.219.176.202|8080|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|11|152.67.72.19|8888|Switzerland|Zurich|Oracle Corporation|
|12|20.99.187.69|8443|United States|Quincy|Microsoft Corporation|
|13|5.78.99.255|50001|United States|Portland|Hetzner Online GmbH|
|14|157.90.236.24|8080|Germany|Nuremberg|Hetzner Online GmbH|
|15|115.144.102.39|10080|South Korea|Gangdong-gu|Korea Telecom|
|16|43.229.148.70|8080|Thailand|Pak Kret|Siamdata Communication Co.|
|17|43.157.66.170|8080|Germany|Frankfurt|Shenzhen Tencent Computer Systems Company Limited|
|18|82.146.48.136|8000|Russia|Irkutsk|CLOUD WebDC collocation|
|19|185.31.160.138|3128|Russia|Moscow|SPACENET|
|20|113.176.118.255|7654|Vietnam|Hoi An|VNPT|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

