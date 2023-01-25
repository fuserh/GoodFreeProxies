# TopFreeProxies
[![GitHub Workflow Status](https://github.com/alanbobs999/topfreeproxies/actions/workflows/get-proxies.yml/badge.svg)](https://github.com/alanbobs999/TopFreeProxies/actions/workflows/get-proxies.yml) 

![Watchers](https://img.shields.io/github/watchers/alanbobs999/topfreeproxies) ![Stars](https://img.shields.io/github/stars/alanbobs999/topfreeproxies) ![Forks](https://img.shields.io/github/forks/alanbobs999/topfreeproxies) ![Vistors](https://visitor-badge.laobi.icu/badge?page_id=alanbobs999.topfreeproxies) ![LICENSE](https://img.shields.io/badge/license-CC%20BY--SA%204.0-green.svg)

[仓库介绍](https://github.com/alanbobs999/TopFreeProxies#仓库介绍) | [使用方法](https://github.com/alanbobs999/TopFreeProxies#使用方法) | [节点信息](https://github.com/alanbobs999/TopFreeProxies#节点信息) | [软件推荐](https://github.com/alanbobs999/TopFreeProxies#客户端选择) | [机场推荐](https://github.com/alanbobs999/TopFreeProxies#机场推荐) | [仓库声明](https://github.com/alanbobs999/TopFreeProxies#仓库声明)

## 仓库介绍
本仓库自动化功能全部基于 `GitHub Actions` 实现，如有需要可以自行 Fork 实现个性化需求，功能配置在 `./utils/config.ini` 配置文件中。

对网络上各免费节点池及博主分享的节点进行测速筛选出较为稳定高速的节点，再导入到仓库中进行分享记录。所筛选的节点链接在仓库 `./sub/sub_list.json` 文件中，其中大部分为其他 `GitHub` 仓库链接，如果大家有好的订阅链接欢迎提交 PR ，这些链接包含的所有节点会合并在仓库 `./sub/sub_merge.txt` 中。

测速筛选后的节点订阅文件在仓库根目录 `Eterniy`(Base64) 和 `Eternity.yaml`(Clash)。同时在仓库的 `./update` 中保留了原始节点链接的的记录。

订阅转换使用 [subconverter](https://github.com/tindy2013/subconverter) 实现，测速功能使用 [LiteSpeedTest](https://github.com/xxf098/LiteSpeedTest) 在 `GitHub Actions` 环境下实现，所以美国节点较多，不能很好代表国内网络环境下节点可用性，目前正在解决这一问题。

虽然是测速筛选过后的节点，但仍然会出现部分节点不可用的情况，遇到这种情况建议选择`Clash`, `Shadowrocket`之类能自动切换低延迟节点的客户端。

## 使用方法
将以下订阅链接导入相应客户端即可。链接中大部分为 SS 协议节点，少量 Vmess, Trojan ,SSR 协议节点，建议选择协议支持完整的客户端。

- [多协议Base64编码](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/Eternity)
- [Clash](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/Eternity.yaml)

另有国内加速链接：

- [多协议Base64编码](https://fastly.jsdelivr.net/gh/alanbobs999/TopFreeProxies@master/Eternity)
- [Clash](https://fastly.jsdelivr.net/gh/alanbobs999/TopFreeProxies@master/Eternity.yaml)

>`Clash`链接所使用的配置在仓库`./update/provider/`中，有相应配置文件和以国家分类的`proxy-provider`。
>
>需要其它配置可使用订阅转换工具自行转换。
>自用在线订阅转换网址：[sub-web-modify](https://sub.v1.mk/)

## 节点信息
### 高速节点
高速节点数量: `93`
<details>
  <summary>展开复制节点</summary>

    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cg6Z+p5Zu9XzAxMjQwMDgiLCJhZGQiOiIxNDQuMjQuNzIuMTI1IiwicG9ydCI6IjM5ODY3IiwidHlwZSI6Im5vbmUiLCJpZCI6IjFjMWQ5NGRjLWU3OWItNGEyNC1kYzlmLTdhZmE5MjUzOWE4MCIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgW1ZNZXNzXSDwn4et8J+HsCBIS+OAkOS7mOi0ueaOqOiNkO+8mmh0dHBzLy90dC5zYnMvdmlw44CRIiwiYWRkIjoiMTYuMTYzLjk1LjEyNyIsInBvcnQiOiIzMjgyNSIsInR5cGUiOiJub25lIiwiaWQiOiI0Y2Q2OWY1Mi00NDQxLTQ0ZWItZDRmNC1mYWE5NzdkNmQ0NzYiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgW1ZNZXNzXSDwn4ev8J+HtSBKUOOAkOS7mOi0ueaOqOiNkO+8mmh0dHBzLy90dC5zYnMvdmlw44CRIiwiYWRkIjoiMTM4LjIuMzUuODEiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiYTA3MzNmYzktNDU3ZS00OThkLWMzNjMtOWVjNzc0YTc0OTQ2IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9qdW4iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7MgVFcgKHlvdXR1YmXpmL/kvJ/np5HmioApIiwiYWRkIjoiaGluZXQtZDA0LndoaXRlY29ubmVjdGIuY29tIiwicG9ydCI6IjY0NDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImNiNzAwMWM3LWU0OTUtNDFhYy1iOTQyLWYyNWY2MDUyMzQxNCIsImFpZCI6IjEiLCJuZXQiOiJ3cyIsInBhdGgiOiIvY2xpZW50YXJlYSIsImhvc3QiOiJoaW5ldC1kMDQud2hpdGVjb25uZWN0Yi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzAxMjQwNzMiLCJhZGQiOiI1MS43OS4xNzMuMjIyIiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6ImE3MmJkN2E3LTczMmQtNDZjMS04Mjc0LWJmMTZiY2EzMGU3OCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvdm1lc3MiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiU0dfQXphZE5ldF8yIiwiYWRkIjoiMTM5Ljk5LjkxLjk1IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjMDE1NjQ1MS00ZWZiLTQ1ZTItODRmYy04ZDMxNWM0NjUwZGIiLCJhaWQiOiIzMiIsIm5ldCI6InRjcCIsInBhdGgiOiIvdm1lc3MiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgW1ZNZXNzXSDwn4ev8J+HtSBKUOOAkOS7mOi0ueaOqOiNkO+8mmh0dHBzLy90dC5zYnMvdmlw44CRIDUiLCJhZGQiOiIxNDAuODMuODYuMTI5IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6Ijg3MDBjZmJkLTcxZGMtNDJiMC04NGYyLTUzY2Q3ZmU1NjQ1YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    ss://YWVzLTI1Ni1nY206UmV4bkJnVTdFVjVBRHhH@85.208.108.18:7001#JP_AzadNet_23
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@85.208.108.19:5000#JP_AzadNet_110
    trojan://a3278882-3614-39cf-a3d6-faefa8c910ab@hk-azure03.xiaohouzi.club:19359?allowInsecure=1&sni=hk-azure03.xiaohouzi.club#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AFAWV09
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzAxMjQwOTMiLCJhZGQiOiIxMTguMTA3LjU3LjE4MCIsInBvcnQiOiIyNzU0MiIsInR5cGUiOiJub25lIiwiaWQiOiIwYzg4YjVmZS1iMTliLTRiMTctOWFiYi05OWEwODI0ZDA0ZjEiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiaGstYXp1cmUwMy54aWFvaG91emkuY2x1YiIsInRscyI6IiJ9
    trojan://a3278882-3614-39cf-a3d6-faefa8c910ab@azhk003.xiaohouzi.club:19357?allowInsecure=1&sni=azhk003.xiaohouzi.club#%F0%9F%87%AD%F0%9F%87%B0%20%E9%A6%99%E6%B8%AFAWV092
    ss://YWVzLTI1Ni1jZmI6ZUlXMERuazY5NDU0ZTZuU3d1c3B2OURtUzIwMXRRMEQ@139.162.41.174:8099#SG_AzadNet_7
    trojan://a3278882-3614-39cf-a3d6-faefa8c910ab@hk-b.xiaohouzi.club:10105?allowInsecure=1&sni=hk-b.xiaohouzi.club#%F0%9F%87%AD%F0%9F%87%B0%20A----a%E9%A6%99%E6%B8%AF%E7%9B%B4%E8%BF%9E01
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpYczlPUlQ0ajY1YjhIcmVacmcwcA@185.160.26.91:1663#JP_AzadNet_4
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgW1ZNZXNzXSDwn4e48J+HrCBTR+OAkOS7mOi0ueaOqOiNkO+8mmh0dHBzLy90dC5zYnMvdmlw44CRIDMiLCJhZGQiOiIxNDYuMTkwLjIwMi45IiwicG9ydCI6IjU3NzExIiwidHlwZSI6Im5vbmUiLCJpZCI6ImZjOTEyODUwLWI2ZGEtNGVjNi05MzQ4LWYzZDFkNzQ3MTkwNiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cg6Z+p5Zu9XzAxMjQwMjMiLCJhZGQiOiIxMy4yMDkuNzIuODciLCJwb3J0IjoiMzYxNDUiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTZhM2JjNWEtYTIyYy00MDkxLWJkOTAtMzE0ZTg3MTc1ZjBhIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cg6Z+p5Zu9XzAxMjQwMTciLCJhZGQiOiIzLjM0LjIuODQiLCJwb3J0IjoiNTI1NTQiLCJ0eXBlIjoibm9uZSIsImlkIjoiOTIwMDJkNDctNTgxNS00YTcxLTk0OWYtYjJhZjE3NDMyMjQ4IiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7Ug5pel5pysXzAxMjQxMjY5IiwiYWRkIjoiNDUuNzYuNDkuMjM3IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIyYWI1NmY3MC0zOWUzLTQ0MjItYmIyZS1kYmZlNTljYjAxZjgiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldF8xNSIsImFkZCI6IjE4Mi4xNi4xLjE5NCIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiIwMGExZGExNC1kNTVmLTVmNzUtZTM0Ni03OWI5ODVlMWE3MjMiLCJhaWQiOiIzMiIsIm5ldCI6IndzIiwicGF0aCI6Ii9vcHQvdmlkZW8vaW1hZ2VzIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cg6Z+p5Zu9XzAxMjQwMTAiLCJhZGQiOiIzLjM1LjEzNC4yMCIsInBvcnQiOiI0NDYyOCIsInR5cGUiOiJub25lIiwiaWQiOiI4ZWM3OGY1NC0wNTFiLTRhZjAtODMyNC0wZDkyNWM3NGM1ZTAiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9vcHQvdmlkZW8vaW1hZ2VzIiwiaG9zdCI6IiIsInRscyI6IiJ9
    ss://YWVzLTI1Ni1nY206Y2RCSURWNDJEQ3duZklO@85.208.108.94:8118#JP_AzadNet_83
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@85.208.108.20:6379#JP_AzadNet_26
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@85.208.108.22:8888#JP_AzadNet_53
    ss://YWVzLTI1Ni1nY206VEV6amZBWXEySWp0dW9T@85.208.108.21:6697#JP_AzadNet_81
    vmess://eyJ2IjoiMiIsInBzIjoiSlBfQXphZE5ldF85IiwiYWRkIjoiMTAzLjI1NC43NC4yOSIsInBvcnQiOiI0NjQ4NiIsInR5cGUiOiJub25lIiwiaWQiOiJkZmQwMDk4MS02ZTA0LTQ5MmItYWJlOS1iOGMwYzg5M2JkMjEiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9vcHQvdmlkZW8vaW1hZ2VzIiwiaG9zdCI6IiIsInRscyI6IiJ9
    trojan://db1e292f-5dbb-451f-a7ec-f85e1c80d5d8@18.177.58.124:50018?allowInsecure=1#JP_18.177.58.124_012420239e7c-636trojan
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHZVBVUHZGOXJmUDdiMXJsSUhrWHhF@34.80.64.94:44561#%F0%9F%87%A8%F0%9F%87%B3%20_TW_%E5%8F%B0%E6%B9%BE%202
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgW1ZNZXNzXSDwn4e48J+HrCBTR+OAkOS7mOi0ueaOqOiNkO+8mmh0dHBzLy90dC5zYnMvdmlw44CRIiwiYWRkIjoiMTUuMjM1LjE0Ny4xODYiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiNmZlYTE2NDktNDI1Yi00MDkyLWJmNTMtMjk3OTIxNTJjOTI1IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9zc2hraXQvRXJ0dXNnODYvNjM1MDE0NjM4YzI2NC8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7Ug5pel5pysIDAxMiIsImFkZCI6Im4xNjcyMTMxMDc5Lmx5cXJkZGUuY24iLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImJmNDg5NTE1LTEzMzUtNDAxNy04NzFlLTZjZDVhMzg0ODhhNyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6Im4xNjcyMTMxMDc5Lmx5cXJkZGUuY24iLCJ0bHMiOiJ0bHMifQ==
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@217.197.161.136:807#SG_AzadNet_9
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@217.197.161.138:805#SG_AzadNet_6
    trojan://cf4295378e209e70d12c5bdd017144dfd1c772d3@43-154-228-196.ipv4.rush.ml:8443?allowInsecure=1&sni=43-154-228-196.ipv4.rush.ml#%F0%9F%87%AD%F0%9F%87%B0%20%5BTrojan%5D%20%F0%9F%87%AD%F0%9F%87%B0%20HK%E3%80%90%E4%BB%98%E8%B4%B9%E6%8E%A8%E8%8D%90%EF%BC%9Ahttps%2F%2Ftt.sbs%2Fvip%E3%80%91
    trojan://182228812d1e0f23@60.249.3.125:3389?allowInsecure=1#TW_AzadNet_9
    trojan://b27c853c-714a-45a5-be55-6451595a1b69@58.152.47.250:443?allowInsecure=1&sni=download2hkt.windowsupdate.lol#HK_AzadNet_6
    trojan://7f9ef59e-20fb-4343-bafc-3a84fa22fe70@104.208.108.110:443?allowInsecure=1&sni=uk01.awcloud.top#HK_AzadNet_16
    trojan://750a29bf-0a40-437f-b120-38de74ae7eaf@210.0.158.220:28443?allowInsecure=1#HK_AzadNet_17
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldF8xOCIsImFkZCI6IjE2LjE2Mi4xODQuMTE1IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjkzYWJhODc2LWQyYTItNDJlNy05YWE5LTYzZjE4YjgzMGIzOCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvZmlsZXN0cmVhbWluZ3NlcnZpY2UvZmlsZXMvMjBmODEzZTItMDM2YS00MmE4LTkyZTItYTNhNTVhMGIyMzliIiwiaG9zdCI6IiIsInRscyI6IiJ9
    trojan://ULJCoEkafFtHeZgEjtAuvgwYuQeepdsu@103.152.221.185:889?allowInsecure=1&sni=o-two.bond#HK_AzadNet_19
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldF8yMyIsImFkZCI6IjQzLjE1NC4zNC40OSIsInBvcnQiOiIyMzE4MyIsInR5cGUiOiJub25lIiwiaWQiOiJiNDAyYTRhZi0yODVhLTQ2M2UtYzNhNy01M2Y5MWVmZGVjNzgiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0Ijoiby10d28uYm9uZCIsInRscyI6IiJ9
    trojan://750a29bf-0a40-437f-b120-38de74ae7eaf@141.147.191.85:28443?allowInsecure=1#JP_AzadNet_1
    trojan://750a29bf-0a40-437f-b120-38de74ae7eaf@155.248.172.87:28443?allowInsecure=1#JP_AzadNet_2
    trojan://28d98f761aca9d636f44db62544628eb@45.66.134.219:443?allowInsecure=1#JP_AzadNet_3
    ssr://NTIuNjkuMTQuMTE0OjgwODE6b3JpZ2luOmFlcy0yNTYtY2ZiOnRsczEuMl90aWNrZXRfYXV0aDpaVUZ2YTJKaFJFNDIvP2dyb3VwPVUxTlNVSEp2ZG1sa1pYSSZyZW1hcmtzPVNsQmZRWHBoWkU1bGRGODQmb2Jmc3BhcmFtPSZwcm90b3BhcmFtPQ
    vmess://eyJ2IjoiMiIsInBzIjoiSlBfQXphZE5ldF8xMCIsImFkZCI6IjE3Mi4xMDQuOTEuMTAwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI5MjcwOTRkMy1kNjc4LTQ3NjMtODU5MS1lMjQwZDBiY2FlODciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2NoYXQiLCJob3N0IjoiIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDAwOSIsImFkZCI6IjIzLjEwNS4xOTkuMTYwIiwicG9ydCI6IjM3NTg0IiwidHlwZSI6Im5vbmUiLCJpZCI6IjYxOTE0ODkzLTM5M2EtNDY4NS1mYzJkLTEzMzI4YmQ4ZTQ5MSIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL2NoYXQiLCJob3N0IjoiIiwidGxzIjoiIn0=
    trojan://dbf9bf9c-2c3f-474a-8031-d4c00666a989@129.146.190.42:443?allowInsecure=1#US_AzadNet_181
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzAxMjQyMDIzIiwiYWRkIjoiMTQ2LjcwLjg3Ljc5IiwicG9ydCI6IjI2MDM0IiwidHlwZSI6Im5vbmUiLCJpZCI6ImViNzIzMmYzLTQ3YWUtNGZlMy1kOGEzLTRiMjVmMDlmMTFjMyIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My04Q0ROIiwiYWRkIjoiNjYuMjM1LjIwMC4yMiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggMS41NXxVUyDnvo7lm715b3V0dWJl6Zi/5Lyf56eR5oqAIDIiLCJhZGQiOiIxNzIuNjQuMTUyLjE1MCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNWY2NGZhNjUtN2IxNC00OWM1LTk1NGQtYWExNWM2YmZjYWNkIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9kb25ndGFpd2FuZy5jb20iLCJob3N0IjoiY2xhc2g2LnNzci1mcmVlLnh5eiIsInRscyI6InRscyJ9
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@51.161.118.38:812#CA_AzadNet_2
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggMi4xM3wg576O5Zu9WW91VHViZeeUsembtumWi+WniyA5IiwiYWRkIjoiMTI4LjE0LjE2Mi40OCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNWY2NGZhNjUtN2IxNC00OWM1LTk1NGQtYWExNWM2YmZjYWNkIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9kb25ndGFpd2FuZy5jb20iLCJob3N0IjoiY2xhc2g2LnNzci1mcmVlLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My02Q0ROIiwiYWRkIjoiMjAzLjMwLjE4OC4xOTAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjE3YjJhMzEzLTM3YTAtNDk0NS1hOGU0LWU2MzM3NTUwNmI0YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQTJESk9QRlQiLCJob3N0IjoibGcxMC5jZmNkbjEueHl6IiwidGxzIjoidGxzIn0=
    ss://YWVzLTI1Ni1nY206UmV4bkJnVTdFVjVBRHhH@167.88.63.82:7002#US_AzadNet_218
    ss://YWVzLTI1Ni1nY206a0RXdlhZWm9UQmNHa0M0@38.114.114.104:8881#US_AzadNet_234
    ss://YWVzLTI1Ni1nY206UENubkg2U1FTbmZvUzI3@38.75.136.34:8090#US_AzadNet_22
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@169.197.143.232:6379#US_AzadNet_275
    ss://YWVzLTI1Ni1nY206ZmFCQW9ENTRrODdVSkc3@142.202.48.7:2376#US_142
    ss://YWVzLTI1Ni1nY206a0RXdlhZWm9UQmNHa0M0@169.197.142.48:8882#US_AzadNet_187
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@193.239.87.134:812#US_AzadNet_13
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xM0NETiIsImFkZCI6IjE5MC45My4yNDQuNCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xQ0ROIiwiYWRkIjoiMjAzLjMwLjE5MS4xOTMiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjE3YjJhMzEzLTM3YTAtNDk0NS1hOGU0LWU2MzM3NTUwNmI0YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQTJESk9QRlQiLCJob3N0IjoibGcxMC5jZmNkbjEueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xMkNETiIsImFkZCI6IjE0MS4xMDEuMTE1LjMyIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6ImxnMTAuY2ZjZG4xLnh5eiIsInRscyI6InRscyJ9
    ss://YWVzLTI1Ni1nY206WEtGS2wyclVMaklwNzQ@38.91.102.30:8008#US_AzadNet_116
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My00Q0ROIiwiYWRkIjoiMjAzLjMwLjE5MC4xOTIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjE3YjJhMzEzLTM3YTAtNDk0NS1hOGU0LWU2MzM3NTUwNmI0YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQTJESk9QRlQiLCJob3N0IjoibGcxMC5jZmNkbjEueHl6IiwidGxzIjoidGxzIn0=
    ss://YWVzLTI1Ni1nY206ZmFCQW9ENTRrODdVSkc3@38.68.135.19:2375#US_AzadNet_16
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggX0NOX+S4reWbvS0+8J+HuvCfh7hfVVNf576O5Zu9XzMiLCJhZGQiOiIyMjMuMTY3LjIwOC42NyIsInBvcnQiOiIxMDAwMyIsInR5cGUiOiJub25lIiwiaWQiOiJjYjcwMDFjNy1lNDk1LTQxYWMtYjk0Mi1mMjVmNjA1MjM0MTQiLCJhaWQiOiIxIiwibmV0IjoidGNwIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xMENETiIsImFkZCI6IjE0MS4xMDEuMTE0LjMyIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6ImxnMTAuY2ZjZG4xLnh5eiIsInRscyI6InRscyJ9
    trojan://cf4295378e209e70d12c5bdd017144dfd1c772d3@3-249-129-98.ipv4.rush.ml:8443?allowInsecure=0#IE_3.249.129.98_010720231715-170trojan
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqfCfh6og5b635Zu9XzAxMjQwMDIiLCJhZGQiOiI1Ljc4LjY4LjI2IiwicG9ydCI6IjQ4ODAzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImYzNzg5ZjE3LWZmZjAtNDMzNy1hY2QzLTM2ZTBiOGJmYTQzYSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    trojan://shefelnak@185.16.206.209:443?allowInsecure=1&sni=content-provider20.cdn-delivery.akamaicd.com#GB_AzadNet_2
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsfCfh7ogMi4wOHxMVeWNouajruWgoSB5b3V0dWJl6Zi/5Lyf56eR5oqAIiwiYWRkIjoiY2xvdWRmbGFyZS5xdWVzdCIsInBvcnQiOiIyMDg2IiwidHlwZSI6Im5vbmUiLCJpZCI6IjgzM2RlOWQyLTk4YzUtNGFjNS05ZDMwLWUzYTdhZDkyOWQxMCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvYXJpZXMiLCJob3N0IjoiYnV5dm0uY2xvdWRmbGFyZS5xdWVzdCIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrPCfh6cgVUsgKGh0dHBzLy9hd2tqLmNmL2t5IOazqOWGjOS9k+mqjOa1geWqkuS9k+acuuWcuil5b3V0dWJl6Zi/5Lyf56eR5oqAIiwiYWRkIjoidnVrMS4wYmFkLmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiOTI3MDk0ZDMtZDY3OC00NzYzLTg1OTEtZTI0MGQwYmNhZTg3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9jaGF0IiwiaG9zdCI6InZ1azEuMGJhZC5jb20iLCJ0bHMiOiJ0bHMifQ==
    trojan://shefelnak@88.150.137.177:443?allowInsecure=1&sni=content-provider4.cdn-delivery.akamaicd.com#%F0%9F%87%AC%F0%9F%87%A7%20%5BTrojan%5D%20GB%E3%80%90%E4%BB%98%E8%B4%B9%E6%8E%A8%E8%8D%90%EF%BC%9Ahttps%2F%2Ftt.sbs%2Fvip%E3%80%91
    vmess://eyJ2IjoiMiIsInBzIjoi5pyq55+lXzAxMjQxODEiLCJhZGQiOiIxNDEuMTAxLjExNS4xMDAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjJiMjE0MTIyLTE5MDYtNDI4YS1iYmI3LWEwMzljYmI3Y2Q1YyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvOUpaRkRUS0UiLCJob3N0IjoiZnIxLnRydW1wMjAyMy5vcmciLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqfCfh6ogREUgKGh0dHBzLy9hd2tqLmNmL2t5IOazqOWGjOS9k+mqjOa1geWqkuS9k+acuuWcuil5b3V0dWJl6Zi/5Lyf56eR5oqAIiwiYWRkIjoiZGUtbHMwMy5uYjEuZnIiLCJwb3J0IjoiNjQ0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiY2I3MDAxYzctZTQ5NS00MWFjLWI5NDItZjI1ZjYwNTIzNDE0IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9jbGllbnRhcmVhIiwiaG9zdCI6ImRlLWxzMDMubmIxLmZyIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS0xMUNETiIsImFkZCI6IjE0MS4xMDEuMTE0LjMwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0MGQ0OTZhNi1jZWViLTQwOTYtYmFlYi00Y2M1MmIyMDU2MjEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0VDVENKMERGIiwiaG9zdCI6ImxnMS50cnVtcDIwMjMudXMiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrPCfh6cg6Iux5Zu9XzAxMjQwNjgiLCJhZGQiOiI4My4yMjkuNjguMjAxIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIyYWI1NmY3MC0zOWUzLTQ0MjItYmIyZS1kYmZlNTljYjAxZjgiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My05Q0ROIiwiYWRkIjoiMTg1LjE2Mi4yMjguMjMwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6ImxnMTAuY2ZjZG4xLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My04Q0ROIDIiLCJhZGQiOiI2Ni4yMzUuMjAwLjIyIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6ImxnMTAuY2ZjZG4xLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HpvCfh7ogW1ZNZXNzXSDwn4em8J+HuiBBVeOAkOS7mOi0ueaOqOiNkO+8mmh0dHBzLy90dC5zYnMvdmlw44CRIiwiYWRkIjoiYXUueWFuZ29uLmNsdWIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6Ijc2ZjZlZDU0LTdmNjEtNDQwNy1mNDlkLWRkMzNkMDdlYmQ4ZiIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6ImxnMTAuY2ZjZG4xLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My02Q0ROIDIiLCJhZGQiOiIyMDMuMzAuMTg4LjE5MCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    trojan://RRy34GGwsPt47SuC@sky998dmit3.xyz:443?allowInsecure=0#%7C%208.33Mb
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xM0NETiIsImFkZCI6IjE5MC45My4yNDUuMyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJvcGxnMS56aHVqaWNuMi5jb20iLCJ0bHMiOiJ0bHMifQ==
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@35.180.158.176:810#FR_AzadNet_33
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xMENETiAyIiwiYWRkIjoiMTQxLjEwMS4xMTQuMzIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjE3YjJhMzEzLTM3YTAtNDk0NS1hOGU0LWU2MzM3NTUwNmI0YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQTJESk9QRlQiLCJob3N0IjoibGcxMC5jZmNkbjEueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiQUVfQXphZE5ldF8yIiwiYWRkIjoiOTUuMTc0LjY4LjIxOCIsInBvcnQiOiIzMTk5MCIsInR5cGUiOiJub25lIiwiaWQiOiJhNmEzN2UwNC01ZTgxLTQ0YzktYmU1My1iYWEzZmY0NmViOGIiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiIifQ==
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@167.88.63.79:3306#%E8%BF%99%E4%BA%9B%E8%8A%82%E7%82%B9%E5%8F%AA%E8%83%BD%E5%A4%87%E7%94%A8%E6%88%96%E8%80%85%E9%98%B2%E6%AD%A2%E5%A4%B1%E8%81%94%EF%BC%8C%E8%99%BD%E7%84%B6%E8%B4%A8%E9%87%8F%E5%B9%B6%E4%B8%8D%E6%98%AF%E5%BE%88%E5%A5%BD%EF%BC%8C%E4%B9%9F%E8%AF%B7%E4%BD%8E%E8%B0%83%E4%BD%BF%E7%94%A8%29%2080
    ss://YWVzLTI1Ni1nY206UmV4bkJnVTdFVjVBRHhH@193.108.117.24:7002#DE_AzadNet_4
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@54.36.174.181:5000#FR_AzadNet_3
    ss://YWVzLTI1Ni1nY206Y2RCSURWNDJEQ3duZklO@51.77.53.200:8118#PL_AzadNet_1
    ss://YWVzLTI1Ni1nY206ZTRGQ1dyZ3BramkzUVk@82.145.41.125:9101#GB_AzadNet_5
    

</details>

### 所有节点
合并节点总数: `1109`
[节点链接](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [pojiezhiyuanjun/freev2](https://github.com/pojiezhiyuanjun/freev2), 节点数量: `129`
- [Alvin9999/pac2](https://github.com/Alvin9999/pac2), 节点数量: `99`
- [xiyaowong/freeFQ](https://github.com/xiyaowong/freeFQ), 节点数量: `156`
- [freefq/free](https://github.com/freefq/free), 节点数量: `38`
- [learnhard-cn/free_proxy_ss](https://github.com/learnhard-cn/free_proxy_ss), 节点数量: `9`
- [vpei/Free-Node-Merge](https://github.com/vpei/Free-Node-Merge), 节点数量: `1`
- [colatiger/v2ray-nodes](https://github.com/colatiger/v2ray-nodes), 节点数量: `36`
- [AzadNetCH/Clash](https://github.com/AzadNetCH/Clash), 节点数量: `2682`
- [ssrsub/ssr](https://github.com/ssrsub/ssr), 节点数量: `213`
- [Leon406/SubCrawler](https://github.com/Leon406/SubCrawler), 节点数量: `313`
- [yu-steven/openit](https://github.com/yu-steven/openit), 节点数量: `1`
- [Jsnzkpg/Jsnzkpg](https://github.com/Jsnzkpg/Jsnzkpg), 节点数量: `20`
- [ermaozi/get_subscribe](https://github.com/ermaozi/get_subscribe), 节点数量: `50`
- [gfwglass 节点池](https://gfwglass.tk), 节点数量: `1`
- [Meteor-1337/Meteor](https://github.com/Meteor-1337/Meteor), 节点数量: `1`
- [ronghuaxueleng/get_v2](https://github.com/ronghuaxueleng/get_v2), 节点数量: `55`
- [anaer/Sub](https://github.com/anaer/Sub), 节点数量: `355`
- [xrayfree/free-ssr-ss-v2ray-vpn-clash](https://github.com/xrayfree/free-ssr-ss-v2ray-vpn-clash), 节点数量: `133`
- [aiboboxx/v2rayfree](https://github.com/aiboboxx/v2rayfree), 节点数量: `38`
- [Pawdroid/Free-servers](https://github.com/Pawdroid/Free-servers), 节点数量: `5`
- [kxswa/k](https://github.com/kxswa/k), 节点数量: `48`
- [Nodefree.org](https://github.com/Fukki-Z/nodefree), 节点数量: `50`
- [Rokate/Proxy-Sub](https://github.com/Rokate/Proxy-Sub), 节点数量: `2801`
- [mianfeifq/share](https://github.com/mianfeifq/share), 节点数量: `211`
- [peasoft/NoMoreWalls](https://github.com/peasoft/NoMoreWalls), 节点数量: `296`
- [ClashNode](https://clashnode.com/f/freenode), 节点数量: `50`

## 客户端选择
### 主流桌面客户端
|                            MacOS                             |                            Linux                             |                           Windows                            | 简易描述                                           |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------------------------------------------------- |
| [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) | [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) | [CFW(Clash For Windows)](https://github.com/Fndroid/clash_for_windows_pkg/releases) | SS, SSR, Trojan, Vmess, VLESS协议支持，策略分流能力强。            |
|     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      |     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      |     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      | SS, SSR, Trojan, Vmess, VLESS, Trojan-Go协议支持（需安装相关插件）。 |
|                              ×                               |                              ×                               |      [V2rayN](https://github.com/2dust/v2rayN/releases)      | SS, Trojan, Vmess, VLESS协议支持，有测速，测延迟功能，支持订阅，二维码，剪贴板导入及手动配置。                 |
|                              ×                               |                              ×                               |    [WinXray](https://github.com/TheMRLL/winxray/releases)    | SS, SSR, Trojan, Vmess, VLESS协议支持，支持自动连接最快节点。            |
|                              ×                               |                              ×                               | [Shadowsocks-windows](https://github.com/shadowsocks/shadowsocks-windows/releases) | SS协议支持， SS 专用客户端。                                       |
|                              ×                               |                              ×                               | [ShadowsocksR-windows](https://github.com/HMBSbige/ShadowsocksR-Windows/releases) | SSR协议支持，SSR 专用客户端。                                      |
|                [Surge](https://nssurge.com/)                 |                              ×                               |                              ×                               | SS, Trojan, Vmess协议支持，著名网络调试工具，策略分流能力强大，需付费。                        |
|   [ClashX](https://github.com/yichengchen/clashX/releases)   |                              ×                               |                              ×                               | SS, SSR, Trojan, Vmess协议支持，占用资源较少。                   |
|      [V2rayU](https://github.com/yanue/V2rayU/releases)      |                              ×                               |                              ×                               | SS, Trojan, Vmess协议支持，支持订阅，二维码，剪贴板导入，手动配置，二维码分享，与 V2RayN 类似。                        |

### 主流移动客户端
|                          iOS/iPadOS                          |                           Android                            | 简易描述                                                     |
| :----------------------------------------------------------: | :----------------------------------------------------------: | ------------------------------------------------------------ |
| [Shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118) | [Shadowrocket](https://play.google.com/store/apps/details?id=com.v2cross.proxy) | SS, SSR, Trojan, Vmess, VLESS协议支持，iOS端需在非国区 App Store 购买，美区售价 $2.99；安卓端非与 iOS 端同一作者，不支持 SSR 协议，免费且内置免费节点。 |
|                [Surge](https://nssurge.com/)                 |                              ×                               | SS, Trojan, Vmess协议支持，iOS 端著名网络调试工具，需付费。                                  |
| [Quantumult X](https://apps.apple.com/us/app/quantumult-x/id1443988620) |                              ×                               | SS, SSR, Trojan, Vmess协议支持，需在非国区AppStore购买，美区售价$4.99。 |
| [Potatso Lite](https://apps.apple.com/us/app/potatso-lite/id1239860606) |                              ×                               | SS, SSR协议支持，需在非国区AppStore购买，免费。              |
|                              ×                               | [Surfboard](https://play.google.com/store/apps/details?id=com.getsurfboard) | SS, SSR, Vmess协议支持，安卓端网络调试软件，兼容 Surge 2 配置。 |
|                              ×                               | [CFA(Clash For Android)](https://github.com/Kr328/ClashForAndroid/releases) | SS, SSR, Trojan, Vmess协议支持。                             |
|                              ×                               |  [SagerNet](https://github.com/SagerNet/SagerNet/releases)   | SS, SSR, Trojan, Vmess, VLESS协议支持。                      |
|                              ×                               | [Shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android/releases) | SS协议支持，安卓专用 SS 客户端。                                                 |
|                              ×                               | [ShadowsocksR-android](https://github.com/HMBSbige/ShadowsocksR-Android/releases) | SSR协议支持，安卓专用 SSR 客户端。                                                |
|                              ×                               |     [V2rayNG](https://github.com/2dust/v2rayNG/releases)     | SS, Trojan, Vmess, VLESS协议支持，v2ray 内核。                           |

## 机场推荐
免费节点失效太快，推荐一些性价比高的机场应急使用。
- [魔戒.net](https://www.mojie.cyou/#/register?code=sAbl0qtT)
  - 按量计费机场, 1¥10G, 10¥130G
  - 所有套餐均是一样的节点与一样的服务，所有套餐流量永不过期，用完为止，不限制客户端数量，最高可提供 2Gbps 峰值
- [大迅云](https://daxun.club/#/register?code=JPmAFPav)
  - 最低月付 5¥50G, 12¥200G, 购买 12¥ 及以上套餐免费领取奈飞 + 迪士尼 Plus 共享号
  - 原生IP负载均衡，流媒体解锁晚高峰油管秒开，主打性价比，有试用
- [阿伟云](https://awcloud.cc/#/register?code=8C18uZwl)
  - 最低月付 1¥ 起, 9.99¥100G
  - 无带宽速率限制，有流媒体解锁，香港 BGP 中继线路

## 仓库声明
订阅节点仅作学习交流使用，只是对网络上节点的优选排序，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。

## 星标统计
[![Star History Chart](https://api.star-history.com/svg?repos=alanbobs999/TopFreeProxies&type=Date)](https://star-history.com/#alanbobs999/TopFreeProxies&Date)
