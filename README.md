
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

> Scraper found **5385** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|303|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|303|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|303|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|946|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|674|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2682|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|206.189.186.128|8080|United States|North Bergen|DigitalOcean, LLC|
|2|34.98.65.22|5222|United States|Kansas City|Google LLC|
|3|64.225.8.82|9983|United States|Clifton|DigitalOcean, LLC|
|4|157.245.156.33|8080|Singapore|Singapore|DigitalOcean, LLC|
|5|206.189.186.128|8080|United States|North Bergen|DigitalOcean, LLC|
|6|5.78.77.144|8080|United States|Portland|Hetzner Online GmbH|
|7|171.243.114.250|10001|Vietnam|Hanoi|Viettel Corporation|
|8|34.98.65.22|5222|United States|Kansas City|Google LLC|
|9|64.225.8.82|9983|United States|Clifton|DigitalOcean, LLC|
|10|45.7.64.4|999|Mexico|Huasca de Ocampo|Maysnet SA De CV|
|11|40.119.236.22|80|Singapore|Singapore|Microsoft Corporation|
|12|144.217.253.209|9300|Canada|Beauharnois|OVH SAS|
|13|177.93.37.87|999|Colombia|Pitalito|TV AZTECA SUCURSAL COLOMBIA|
|14|190.6.23.218|999|Venezuela|Caucaguito|Net Uno|
|15|103.66.10.92|9898|India|Kharar|Nitya Internet Private Limited|
|16|201.150.118.46|999|Mexico|Actopan|Hulux Telecomunicaciones|
|17|198.245.78.108|53128|United States|Buffalo|Server Mania Inc|
|18|110.138.254.235|8080|Indonesia|Surabaya|PT. TELKOM INDONESIA|
|19|37.120.192.154|8080|Netherlands|Amsterdam|M247 Europe SRL|
|20|158.160.56.149|8080|Russia|Moscow|Yandex.Cloud LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

