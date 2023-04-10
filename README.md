
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

> Scraper found **7552** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|729|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|729|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|729|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1994|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1155|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|3420|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|143.244.205.72|1080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|2|152.228.206.188|80|France|Paris|OVH SAS|
|3|45.137.65.193|8080|Netherlands|Amsterdam|Zomro B.V.|
|4|158.69.71.245|9300|Canada|Montreal|OVH SAS|
|5|104.40.148.100|8080|Netherlands|Amsterdam|Microsoft Corporation|
|6|20.99.187.69|8443|United States|Quincy|Microsoft Corporation|
|7|13.93.68.176|8080|Netherlands|Amsterdam|Microsoft Corporation|
|8|5.8.53.7|18081|Russia|St Petersburg|Petersburg Internet Network ltd|
|9|5.161.180.82|50001|United States|Ashburn|Hetzner Online GmbH|
|10|20.99.187.69|8443|United States|Quincy|Microsoft Corporation|
|11|158.69.53.132|9300|Canada|Montreal|OVH SAS|
|12|66.70.178.214|9300|Canada|Beauharnois|OVH SAS|
|13|152.67.72.19|8888|Switzerland|Zurich|Oracle Corporation|
|14|210.172.199.88|8080|Japan|Gifu|KITAGATA|
|15|115.96.208.124|8080|India|Mumbai|Hathway IP over Cable Internet Access|
|16|222.254.11.241|8080|Vietnam|Hanoi|VietNam Post and Telecom Corporation|
|17|47.244.32.96|80|Hong Kong|Central|Alibaba.com LLC|
|18|103.121.149.69|8080|Indonesia|Jakarta|PT EMERIO INDONESIA|
|19|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|20|18.163.110.75|8080|Hong Kong|Hong Kong|Amazon Technologies Inc.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

