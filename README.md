
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

> Scraper found **6215** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|459|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|459|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|459|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1345|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|872|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2915|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|209.126.9.81|3128|United States|St Louis|Contabo Inc.|
|2|210.172.199.88|8080|Japan|Gifu|KITAGATA|
|3|209.126.9.81|3128|United States|St Louis|Contabo Inc.|
|4|201.6.117.108|8082|Brazil|São Paulo|Claro NXT Telecomunicacoes Ltda|
|5|100.21.80.30|80|United States|Portland|Amazon.com, Inc.|
|6|102.165.4.52|8001|United States|Ashburn|Tier.Net Technologies LLC|
|7|51.159.0.236|3128|France|Paris|SCALEWAY|
|8|20.241.236.196|3128|United States|Boydton|Microsoft Corporation|
|9|159.192.233.231|8080|Thailand|Sing Buri|CAT-BB|
|10|20.241.236.196|3128|United States|Boydton|Microsoft Corporation|
|11|8.219.176.202|8080|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|12|103.69.108.78|8191|Philippines|Santiago|CITI Cableworld Inc.|
|13|102.165.4.52|8001|United States|Ashburn|Tier.Net Technologies LLC|
|14|45.136.58.22|8888|Kazakhstan|Oral|Megahost Kazakhstan TOO|
|15|190.210.223.90|8080|Argentina|Buenos Aires|NSS S.A.|
|16|190.15.158.183|8080|Cuba|Havana|Empresa de Telecomunicaciones de Cuba, S.A.|
|17|5.78.92.68|50001|United States|Portland|Hetzner Online GmbH|
|18|115.144.101.201|10001|South Korea|Gangdong-gu|Korea Telecom|
|19|64.225.8.82|9998|United States|Clifton|DigitalOcean, LLC|
|20|103.121.149.69|8080|Indonesia|Jakarta|PT EMERIO INDONESIA|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

