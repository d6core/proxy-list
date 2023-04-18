
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

> Scraper found **5951** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|370|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|370|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|370|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1253|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|822|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2793|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|115.144.101.201|10001|South Korea|Gangdong-gu|Korea Telecom|
|2|115.144.102.39|10080|South Korea|Gangdong-gu|Korea Telecom|
|3|100.21.80.30|9480|United States|Portland|Amazon.com, Inc.|
|4|148.251.123.98|7777|Germany|Sangerhausen|Hetzner Online GmbH|
|5|91.107.207.116|8080|Germany|Frankfurt Am Main|Hetzner Online AG|
|6|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|7|154.70.107.81|3128|Cameroon|Douala|MTN Network Solutions (Cameroon)|
|8|186.251.123.100|8080|Brazil|Sertanopolis|N G B Pires & CIA LTDA|
|9|102.165.4.52|8001|United States|Ashburn|Tier.Net Technologies LLC|
|10|100.21.80.30|9480|United States|Portland|Amazon.com, Inc.|
|11|210.186.107.228|8083|Malaysia|Johor Bahru|ADSL Streamyx Telekom Malaysia|
|12|5.161.180.82|50001|United States|Ashburn|Hetzner Online GmbH|
|13|210.172.199.88|8080|Japan|Gifu|KITAGATA|
|14|51.159.0.236|3128|France|Paris|SCALEWAY|
|15|8.219.176.202|8080|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|16|5.161.180.82|50001|United States|Ashburn|Hetzner Online GmbH|
|17|186.159.6.165|1994|Colombia|Medellín|Edatel S.a. E.S.P|
|18|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|19|201.182.251.142|999|Colombia|Pasto|SP SISTEMAS PALACIOS LTDA|
|20|157.90.236.24|8080|Germany|Nuremberg|Hetzner Online GmbH|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

