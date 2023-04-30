
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

> Scraper found **5897** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|400|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|400|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|400|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1228|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|820|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2766|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|192.227.128.179|8080|United States|Buffalo|ColoCrossing|
|2|205.213.80.8|8009|United States|Siren|WiscNet|
|3|204.2.218.145|8080|United States|Calhoun|North Georgia Network Cooperative, Inc.|
|4|96.95.164.41|3128|United States|Deep River|Comcast Cable Communications, LLC|
|5|205.213.80.8|8009|United States|Siren|WiscNet|
|6|40.85.152.26|8080|United States|San Francisco|Microsoft Corporation|
|7|35.247.197.36|3129|Brazil|Sao Paulo|Google LLC|
|8|40.119.236.22|80|Singapore|Singapore|Microsoft Corporation|
|9|201.229.250.21|8080|Dominican Republic|Santo Domingo Este|Compañía Dominicana de Teléfonos S. A.|
|10|86.98.38.141|8080|United Arab Emirates|Sharjah|Emirates Telecommunications Corporation|
|11|115.144.102.39|10080|South Korea|Gangdong-gu|Korea Telecom|
|12|103.69.108.78|8191|Philippines|Santiago|CITI Cableworld Inc.|
|13|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|14|20.241.236.196|3128|United States|Boydton|Microsoft Corporation|
|15|34.140.70.242|8080|Belgium|Brussels|Google LLC|
|16|5.189.184.6|80|Germany|Nuremberg|Contabo GmbH|
|17|190.202.3.22|32650|Venezuela|Caracas|CANTV Servicios, Venezuela|
|18|65.108.48.232|8080|Finland|Helsinki|Hetzner Online GmbH|
|19|76.181.159.53|32650|United States|Byesville|Charter Communications Inc|
|20|64.225.4.12|9992|United States|Clifton|DigitalOcean, LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

