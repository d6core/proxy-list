
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

> Scraper found **6305** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|421|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|421|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|421|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1461|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|886|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2875|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|192.154.253.67|8123|United States|Charlotte|Tier.Net Technologies LLC|
|2|20.241.236.196|3128|United States|Boydton|Microsoft Corporation|
|3|65.108.245.144|8080|Finland|Helsinki|Hetzner Online GmbH|
|4|157.230.34.219|3128|Singapore|Singapore|DigitalOcean, LLC|
|5|5.189.184.6|80|Germany|Nuremberg|Contabo GmbH|
|6|167.71.205.47|8080|Singapore|Singapore|DigitalOcean, LLC|
|7|20.241.236.196|3128|United States|Boydton|Microsoft Corporation|
|8|5.78.92.235|8080|United States|Portland|Hetzner Online GmbH|
|9|8.218.239.151|3128|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|10|43.229.149.154|8080|Thailand|Pak Kret|Siamdata Communication Co.|
|11|152.228.206.188|80|France|Paris|OVH SAS|
|12|8.219.176.202|8080|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|13|70.15.116.177|8888|United States|Ephrata|PenTeleData Inc.|
|14|115.144.101.201|10001|South Korea|Gangdong-gu|Korea Telecom|
|15|109.195.230.143|8080|Russia|Rostov-on-Don|CJSC "ER-Telecom Holding" Rostov-na-Donu branch|
|16|5.78.87.84|8080|United States|Portland|Hetzner Online GmbH|
|17|144.217.240.185|9300|Canada|Beauharnois|OVH SAS|
|18|103.69.108.78|8191|Philippines|Santiago|CITI Cableworld Inc.|
|19|200.25.254.193|54240|Colombia|Neiva|Andinet ON Line|
|20|185.15.172.212|3128|Russia|Moscow|SafeData LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

