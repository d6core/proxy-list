
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

> Scraper found **5937** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|381|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|381|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|381|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1236|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|776|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2842|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|100.21.80.30|80|United States|Portland|Amazon.com, Inc.|
|2|8.219.176.202|8080|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|3|45.79.24.54|8080|United States|Richardson|Akamai Technologies, Inc.|
|4|43.156.100.152|80|Singapore|Singapore|Shenzhen Tencent Computer Systems Company Limited|
|5|100.21.80.30|80|United States|Portland|Amazon.com, Inc.|
|6|45.79.24.54|8080|United States|Richardson|Akamai Technologies, Inc.|
|7|40.119.236.22|80|Singapore|Singapore|Microsoft Corporation|
|8|167.71.205.47|8080|Singapore|Singapore|DigitalOcean, LLC|
|9|204.14.58.35|80|United States|Delhi|DTC Cable|
|10|5.78.45.87|8080|United States|Portland|Hetzner Online GmbH|
|11|51.161.118.103|8118|Canada|Beauharnois|OVH SAS|
|12|152.228.206.188|80|France|Paris|OVH SAS|
|13|103.69.108.78|8191|Philippines|Santiago|CITI Cableworld Inc.|
|14|114.7.27.98|8080|Indonesia|Balikpapan|PT. INDOSAT Tbk|
|15|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|16|77.52.178.157|8087|Ukraine|Kyiv|UMC|
|17|192.109.244.221|8080|Poland|Lodz|IWACOM Sp. z o.o.|
|18|159.138.130.126|8999|Hong Kong|Hong Kong|Huawei International Pte. Ltd.|
|19|210.172.199.88|8080|Japan|Gifu|KITAGATA|
|20|185.15.172.212|3128|Russia|Moscow|SafeData LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

