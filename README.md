
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

> Scraper found **6575** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|422|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|422|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|422|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1532|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|927|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|3033|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|43.157.66.170|8080|Germany|Frankfurt|Shenzhen Tencent Computer Systems Company Limited|
|2|204.2.218.145|8080|United States|Calhoun|North Georgia Network Cooperative, Inc.|
|3|204.2.218.145|8080|United States|Calhoun|North Georgia Network Cooperative, Inc.|
|4|38.105.209.110|8080|United States|New York|Contabo Inc.|
|5|8.219.176.202|8080|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|6|8.218.239.151|3128|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|7|185.81.98.16|3131|Netherlands|Naaldwijk|WorldStream B.V.|
|8|45.81.130.120|45787|United States|Los Angeles|Zenlayer Inc|
|9|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|10|168.11.52.41|8080|United States|Lyons|Board of Regents of the University System of Georgia|
|11|198.59.191.234|8080|United States|Carlsbad|TDS TELECOM|
|12|198.59.191.234|8080|United States|Carlsbad|TDS TELECOM|
|13|95.217.135.29|8080|Finland|Helsinki|Hetzner Online GmbH|
|14|38.105.209.110|8080|United States|New York|Contabo Inc.|
|15|109.123.232.106|8080|Singapore|Singapore|Contabo Asia Private Limited|
|16|54.92.167.233|8118|United States|Ashburn|Amazon.com, Inc.|
|17|152.67.72.19|8888|Switzerland|Zurich|Oracle Corporation|
|18|20.24.12.255|3128|Singapore|Singapore|Microsoft Corporation|
|19|103.69.108.78|8191|Philippines|Santiago|CITI Cableworld Inc.|
|20|103.121.149.69|8080|Indonesia|Jakarta|PT EMERIO INDONESIA|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

