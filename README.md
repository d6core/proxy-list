
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

> Scraper found **6084** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|408|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|408|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|408|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1290|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|897|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2814|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|68.132.12.228|8888|United States|Staten Island|Verizon Communications|
|2|20.203.133.123|3128|Switzerland|Zurich|Microsoft Corporation|
|3|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|4|43.134.211.34|3128|Hong Kong|Hong Kong|Shenzhen Tencent Computer Systems Company Limited|
|5|5.159.100.224|8080|Russia|St Petersburg|OOO "Network of data-centers "Selectel"|
|6|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|7|5.161.110.95|50001|United States|Ashburn|Hetzner Online GmbH|
|8|115.144.101.201|10001|South Korea|Gangdong-gu|Korea Telecom|
|9|152.228.206.188|80|France|Paris|OVH SAS|
|10|8.219.176.202|8080|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|11|68.132.12.228|8888|United States|Staten Island|Verizon Communications|
|12|34.125.140.58|3128|United States|Las Vegas|Google LLC|
|13|43.156.100.152|80|Singapore|Singapore|Shenzhen Tencent Computer Systems Company Limited|
|14|89.208.35.81|3128|Russia|Moscow|DINET-HOSTING|
|15|40.119.236.22|80|Singapore|Singapore|Microsoft Corporation|
|16|51.159.0.236|3128|France|Paris|SCALEWAY|
|17|103.69.108.78|8191|Philippines|Santiago|CITI Cableworld Inc.|
|18|167.99.238.124|80|United States|North Bergen|DigitalOcean, LLC|
|19|5.78.42.62|50001|United States|Portland|Hetzner Online GmbH|
|20|45.136.58.51|8888|Kazakhstan|Oral|Megahost Kazakhstan TOO|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

