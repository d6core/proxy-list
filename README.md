
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

> Scraper found **6155** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|406|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|406|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|406|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1307|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|834|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2931|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|100.21.80.30|80|United States|Portland|Amazon.com, Inc.|
|2|20.241.236.196|3128|United States|Boydton|Microsoft Corporation|
|3|40.119.236.22|80|Singapore|Singapore|Microsoft Corporation|
|4|43.157.66.170|8080|Germany|Frankfurt|Shenzhen Tencent Computer Systems Company Limited|
|5|8.219.176.202|8080|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|6|100.21.80.30|80|United States|Portland|Amazon.com, Inc.|
|7|115.144.101.201|10001|South Korea|Gangdong-gu|Korea Telecom|
|8|210.172.199.88|8080|Japan|Gifu|KITAGATA|
|9|20.241.236.196|3128|United States|Boydton|Microsoft Corporation|
|10|115.144.102.39|10080|South Korea|Gangdong-gu|Korea Telecom|
|11|191.98.179.21|3128|Peru|Lima|Optical Technologies S.A.C.|
|12|159.138.130.126|8999|Hong Kong|Hong Kong|Huawei International Pte. Ltd.|
|13|37.210.74.196|8080|Qatar|Doha|Ooredoo Q.S.C.|
|14|64.225.8.118|9976|United States|Clifton|DigitalOcean, LLC|
|15|94.102.196.89|1500|Ireland|Dublin|Regional Broadband Ireland Ltd|
|16|103.164.118.86|8080|Indonesia|Jakarta|SOLUSINET|
|17|181.209.118.34|999|Argentina|Benavidez|ARSAT - Empresa Argentina de Soluciones Satelitales S.A|
|18|51.79.50.31|9300|Canada|Beauharnois|OVH SAS|
|19|210.172.199.88|8080|Japan|Gifu|KITAGATA|
|20|65.108.230.239|37917|Finland|Helsinki|Hetzner Online GmbH|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

