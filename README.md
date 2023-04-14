
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

> Scraper found **7015** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|888|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|888|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|888|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1731|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1107|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|3094|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|20.241.236.196|3128|United States|Boydton|Microsoft Corporation|
|2|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|3|138.197.155.136|8080|Canada|Toronto|DigitalOcean, LLC|
|4|128.90.145.218|8118|Belgium|Brussels|Powerhouse Management, Inc.|
|5|20.241.236.196|3128|United States|Boydton|Microsoft Corporation|
|6|115.144.102.39|10080|South Korea|Gangdong-gu|Korea Telecom|
|7|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|8|5.78.45.181|8080|United States|Portland|Hetzner Online GmbH|
|9|8.219.176.202|8080|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|10|5.78.65.205|8080|United States|Portland|Hetzner Online GmbH|
|11|51.79.50.22|9300|Canada|Beauharnois|OVH SAS|
|12|5.78.71.36|8080|United States|Portland|Hetzner Online GmbH|
|13|5.78.66.187|8080|United States|Portland|Hetzner Online GmbH|
|14|5.78.41.146|8080|United States|Portland|Hetzner Online GmbH|
|15|149.102.243.172|8080|United States|Los Angeles|Datacamp Limited|
|16|210.172.199.88|8080|Japan|Gifu|KITAGATA|
|17|45.136.238.69|8080|Thailand|Nonthaburi|Siamdata Communication Co., ltd.|
|18|5.8.53.7|18081|Russia|St Petersburg|Petersburg Internet Network ltd|
|19|103.92.26.190|4002|Vietnam|Ho Chi Minh City|TLSOFT|
|20|116.0.61.122|3128|Pakistan|Karachi|Telecard|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

