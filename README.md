
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

> Scraper found **7167** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|564|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|564|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|564|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1647|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1206|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|3331|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|52.4.150.19|8080|United States|Ashburn|Amazon.com, Inc.|
|2|20.159.154.112|8080|United States|Boydton|Microsoft Corporation|
|3|20.210.27.147|3129|Japan|Tokyo|Microsoft Corporation|
|4|20.210.39.170|3129|Japan|Tokyo|Microsoft Corporation|
|5|54.37.21.230|3128|France|Gravelines|OVH SAS|
|6|198.59.191.234|8080|United States|Carlsbad|TDS TELECOM|
|7|54.39.184.149|3128|Canada|Beauharnois|OVH SAS|
|8|152.67.72.19|8888|Switzerland|Zurich|Oracle Corporation|
|9|20.210.37.125|3129|Japan|Tokyo|Microsoft Corporation|
|10|54.39.182.198|3128|Canada|Beauharnois|OVH SAS|
|11|64.52.80.250|8080|United States|Los Angeles|BL Networks|
|12|52.4.150.19|8080|United States|Ashburn|Amazon.com, Inc.|
|13|20.210.25.252|3129|Japan|Tokyo|Microsoft Corporation|
|14|64.52.80.250|8080|United States|Los Angeles|BL Networks|
|15|20.210.34.43|3129|Japan|Tokyo|Microsoft Corporation|
|16|20.210.26.15|3129|Japan|Tokyo|Microsoft Corporation|
|17|20.210.27.159|3129|Japan|Tokyo|Microsoft Corporation|
|18|20.69.79.158|8443|United States|Quincy|Microsoft Corporation|
|19|198.59.191.234|8080|United States|Carlsbad|TDS TELECOM|
|20|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

