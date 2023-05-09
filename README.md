
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

> Scraper found **5538** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|200|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|200|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|200|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|959|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|891|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2605|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|184.72.169.187|3128|United States|Ashburn|Amazon.com|
|2|34.98.65.22|5222|United States|Kansas City|Google LLC|
|3|18.130.4.159|3128|United Kingdom|London|Amazon Technologies Inc.|
|4|35.177.254.13|3128|United Kingdom|London|Amazon Technologies Inc.|
|5|20.99.187.69|8443|United States|Quincy|Microsoft Corporation|
|6|184.72.169.187|3128|United States|Ashburn|Amazon.com|
|7|5.161.110.95|50272|United States|Ashburn|Hetzner Online GmbH|
|8|20.99.187.69|8443|United States|Quincy|Microsoft Corporation|
|9|20.69.79.158|8443|United States|Quincy|Microsoft Corporation|
|10|34.98.65.22|5222|United States|Kansas City|Google LLC|
|11|115.96.208.124|8080|India|Mumbai|Hathway IP over Cable Internet Access|
|12|181.189.135.90|8080|Guatemala|Guatemala City|Comcel Guatemala S.A.|
|13|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|14|113.53.231.133|3129|Thailand|Ban Pho|TOT Public Company Limited|
|15|135.181.14.45|5959|Finland|Helsinki|Hetzner Online GmbH|
|16|194.5.25.34|443|Singapore|Singapore|Mod Mission Critical LLC|
|17|115.144.101.201|10001|South Korea|Gangdong-gu|Korea Telecom|
|18|103.121.149.69|8080|Indonesia|Jakarta|PT EMERIO INDONESIA|
|19|37.120.192.154|8080|Netherlands|Amsterdam|M247 Europe SRL|
|20|118.99.103.228|8080|Indonesia|Jakarta|Biznet Metronet|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

