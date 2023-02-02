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
高速节点数量: `92`
<details>
  <summary>展开复制节点</summary>

    trojan://da777aae-defb-41d0-a183-2c27da2b4677@150.230.96.103:443?allowInsecure=1&sni=150.230.96.103#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2810%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7Ug5pel5pysIDAwNiIsImFkZCI6Im00LjQwMDEwMDEwLnh5eiIsInBvcnQiOiIzNzEyMSIsInR5cGUiOiJub25lIiwiaWQiOiI1NzVlNGQ5Mi0xMDU2LTQ0YzItOGNhYy03NWVmMWM4NTlhZDUiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTUwLjIzMC45Ni4xMDMiLCJ0bHMiOiJ0bHMifQ==
    trojan://8d2d5953-d649-4034-94f2-72f2df2623da@168.138.44.176:443?allowInsecure=1#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2814%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgX1NHX+aWsOWKoOWdoSAyIDIiLCJhZGQiOiJ2c2cxLjBiYWQuY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI5MjcwOTRkMy1kNjc4LTQ3NjMtODU5MS1lMjQwZDBiY2FlODciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2NoYXQiLCJob3N0IjoidnNnMS4wYmFkLmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cg6Z+p5Zu9XzAyMDIwMjUiLCJhZGQiOiIxMy4xMjUuMjM3LjExMiIsInBvcnQiOiI0NTg2OSIsInR5cGUiOiJub25lIiwiaWQiOiI2Y2E5NjM1MS1kNGNlLTQ4ZDMtZTAyZC03YWJlN2M0ZjU0ZmUiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9jaGF0IiwiaG9zdCI6InZzZzEuMGJhZC5jb20iLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzAyMDIwMjMiLCJhZGQiOiIxMzguMi43OC4xOTIiLCJwb3J0IjoiMTA1MTIiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTg3ODFlZWUtYmFiYS02NjY2LWJhYmEtMmNhMGFkYTY1NjhiIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvY2hhdCIsImhvc3QiOiJ2c2cxLjBiYWQuY29tIiwidGxzIjoiIn0=
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@139.99.120.234:8000#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29%2817%29
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@85.208.108.93:6379#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2817%29
    ss://YWVzLTI1Ni1nY206cEtFVzhKUEJ5VFZUTHRN@85.208.108.94:4444#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2822%29
    ss://YWVzLTI1Ni1nY206Y2RCSURWNDJEQ3duZklO@85.208.108.19:8118#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2879%29
    ss://YWVzLTI1Ni1nY206ZmFCQW9ENTRrODdVSkc3@85.208.108.90:2376#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2850%29
    ss://YWVzLTI1Ni1nY206cEtFVzhKUEJ5VFZUTHRN@85.208.108.18:443#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2827%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzAyMDIwMDciLCJhZGQiOiI0My4xMzQuMTc3LjEzMCIsInBvcnQiOiIyNzgwMyIsInR5cGUiOiJub25lIiwiaWQiOiI0Mjc3OWU3MS0yZTZiLTRlYjQtOWY0My1kZTRlNTdiYjhiMmIiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9jaGF0IiwiaG9zdCI6InZzZzEuMGJhZC5jb20iLCJ0bHMiOiIifQ==
    ss://YWVzLTI1Ni1jZmI6ZUlXMERuazY5NDU0ZTZuU3d1c3B2OURtUzIwMXRRMEQ@139.162.41.174:8099#SG_127
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@85.208.108.22:8888#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2897%29
    ss://YWVzLTI1Ni1nY206ZTRGQ1dyZ3BramkzUVk@85.208.108.58:9101#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2864%29
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@54.254.147.251:804#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29%2821%29
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@85.208.108.21:6379#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2820%29
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@85.208.108.20:6379#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2821%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgU0coQXphZE5ldC50Lm1lKSg3KSIsImFkZCI6IjEzOS45OS45MS45NSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzAxNTY0NTEtNGVmYi00NWUyLTg0ZmMtOGQzMTVjNDY1MGRiIiwiYWlkIjoiMzIiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL2NoYXQiLCJob3N0IjoidnNnMS4wYmFkLmNvbSIsInRscyI6IiJ9
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@85.208.108.60:6379#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2818%29
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@85.208.108.59:6379#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2819%29
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpYczlPUlQ0ajY1YjhIcmVacmcwcA@185.160.26.91:1664#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%28171%29
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@81.90.189.41:810#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29%2818%29
    trojan://0c6a3341e8d5ab17@103.172.116.196:3389?allowInsecure=1#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29%2814%29
    trojan://b291d129-ee55-4801-a9b8-b5316e5c37b7@138.2.113.84:443?allowInsecure=1#%F0%9F%87%B0%F0%9F%87%B7%20KR%28AzadNet.t.me%29%284%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzAyMDIwMjIiLCJhZGQiOiIyMDYuMTg5LjE0Ny42OSIsInBvcnQiOiIyMDQzNyIsInR5cGUiOiJub25lIiwiaWQiOiJiMDcxOThkMy04YzJkLTQxNjYtZGYwNS1jYTU0ZWE1ZWU2Y2EiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@13.214.212.124:443#%F0%9F%87%B8%F0%9F%87%AC%20_SG_%E6%96%B0%E5%8A%A0%E5%9D%A1%204
    trojan://0c6a3341e8d5ab17@103.172.116.121:3389?allowInsecure=1#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29%2815%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgX1VTX+e+juWbvS0+8J+Hr/Cfh7VfSlBf5pel5pysIiwiYWRkIjoibWluZzIua2l3aXJlaWNoLmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMThlNWY0MGYtYmRhNi00YzE1LTkzMzQtZTg3Y2RhNjA0N2FmIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9yYXkiLCJob3N0IjoibWluZzIua2l3aXJlaWNoLmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7MgZ2l0aHViLmNvbS9mcmVlZnEgLSDlj7Dmub7nnIHlj7DljJfluILkuK3ljY7nlLXkv6EgNDEiLCJhZGQiOiJoaW5ldDEyNjEuZ2Z3aXNiZXN0Lnh5eiIsInBvcnQiOiIyMjQiLCJ0eXBlIjoibm9uZSIsImlkIjoiMjI4NTEzM2UtYjliYS0zZmI1LWEyNDYtOWM3ZGRjYzJjZDdhIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvcmF5IiwiaG9zdCI6Im1pbmcyLmtpd2lyZWljaC5jb20iLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cg6Z+p5Zu9XzAyMDIwMDIiLCJhZGQiOiIzLjM1LjEzNC4yMCIsInBvcnQiOiI0NDYyOCIsInR5cGUiOiJub25lIiwiaWQiOiI4ZWM3OGY1NC0wNTFiLTRhZjAtODMyNC0wZDkyNWM3NGM1ZTAiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9yYXkiLCJob3N0IjoibWluZzIua2l3aXJlaWNoLmNvbSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzAyMDIwMjEiLCJhZGQiOiIxNDYuMTkwLjIwMi45IiwicG9ydCI6IjU3NzExIiwidHlwZSI6Im5vbmUiLCJpZCI6ImZjOTEyODUwLWI2ZGEtNGVjNi05MzQ4LWYzZDFkNzQ3MTkwNyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgW1ZNZXNzXSDwn4e48J+HrCBTR+OAkOS7mOi0ueaOqOiNkO+8mmh0dHBzLy90dC5zYnMvdmlw44CRIiwiYWRkIjoiMTUuMjM1LjE0Ny4xODYiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiNmZlYTE2NDktNDI1Yi00MDkyLWJmNTMtMjk3OTIxNTJjOTI1IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9zc2hraXQvRXJ0dXNnODYvNjM1MDE0NjM4YzI2NC8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@148.66.56.99:812#%F0%9F%87%AD%F0%9F%87%B0%20HK%28AzadNet.t.me%29%289%29
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@217.197.161.136:811#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29%2827%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7Ug5pel5pysXzAyMDIxMDciLCJhZGQiOiIxMDMuMjU0Ljc0LjE2OCIsInBvcnQiOiIyMjk5MyIsInR5cGUiOiJub25lIiwiaWQiOiJkMjZiY2ZiMi1hYTlhLTQ5MjMtYTdjYS0wMGU0MmY1YTQ5MmIiLCJhaWQiOiI1MyIsIm5ldCI6InRjcCIsInBhdGgiOiIvc3Noa2l0L0VydHVzZzg2LzYzNTAxNDYzOGMyNjQvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzAyMDIwMDQiLCJhZGQiOiIxOC4xNDMuMTIzLjM1IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjY4ZGY0ODM4LTQ2ZDAtNGI1Yi1jM2YwLWE0MGVjNzA2MzI0NSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgSlAoQXphZE5ldC50Lm1lKSg0KSIsImFkZCI6IjE2OC4xMzguMTk0LjI0MyIsInBvcnQiOiIzMzQyMSIsInR5cGUiOiJub25lIiwiaWQiOiI5NGU1NmZmOS1jY2YxLTQxNGUtYTExNC00NmUwYTc5ZjY2MTQiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgSlAoQXphZE5ldC50Lm1lKSg4KSIsImFkZCI6IjEzOC4yLjM5LjY3IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6ImFiMzM1Yzg4LWQxNGEtNGU2Ny1iNTJjLTU0ZWQ4YmU4MGM0OSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgSlAoQXphZE5ldC50Lm1lKSgzKSIsImFkZCI6IjE2OC4xMzguMjA2LjE0MSIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiJhZDA1ZTAxZi1jMmMwLTQxZGEtZTc5Yy1mZjY4MjM3MzE3ZjciLCJhaWQiOiIwIiwibmV0IjoiaHR0cCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    trojan://c19d1432-8b3e-4818-8837-3d160cf65908@138.2.45.243:443?allowInsecure=1#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2812%29
    trojan://shenmegui@37.123.196.250:28893?allowInsecure=1#%F0%9F%87%AD%F0%9F%87%B0%20HK%28AzadNet.t.me%29%286%29
    trojan://6ee96394-2a43-43dc-898b-bbf68a237310@18.177.58.124:50286?allowInsecure=1&sni=jp-tk-31.fuckjdieng.uk#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2815%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDEzOSIsImFkZCI6IjE5Mi4yMjcuMTc0LjciLCJwb3J0IjoiMTgzMzIiLCJ0eXBlIjoibm9uZSIsImlkIjoiOGM0MDBhNWYtZGM4Yi00MTk3LTkyZWQtMDk4ZDVmYTdlMjE0IiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6ImpwLXRrLTMxLmZ1Y2tqZGllbmcudWsiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC00IiwiYWRkIjoiMjMuMjI3LjM4LjI1IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDEwMCIsImFkZCI6IjEyOS4xNTkuNDEuMjMzIiwicG9ydCI6IjMyNTg2IiwidHlwZSI6Im5vbmUiLCJpZCI6IjM0MWE5MTgyLWM0MjMtNDk5Yy1jNDZlLWQxNzgzOGIyOTAzNyIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC0xNiIsImFkZCI6IjIwMy4zMC4xOTEuMTkxIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@72.140.224.195:812#%F0%9F%87%A8%F0%9F%87%A6%20CA%28AzadNet.t.me%29%2859%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC0xNyIsImFkZCI6IjE5OC40MS4yMTIuMTIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImM1YTJkN2I4LWJmODQtNGY5Ny04NTc3LWI5Yjg3ZjJiYWFmNyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQVVJS044QVUiLCJob3N0Ijoib3BsZzEuY2ZjZG4yLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMS40NHxVU2h0dHBzYXdramNma3kg5rOo5YaM5L2T6aqM5rWB5aqS5L2T5py65Zy6eW91dHViZemYv+S8n+enkeaKgCAzIiwiYWRkIjoiMjAzLjMwLjE5MS4yMCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNWY2NGZhNjUtN2IxNC00OWM1LTk1NGQtYWExNWM2YmZjYWNkIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9kb25ndGFpd2FuZy5jb20iLCJob3N0IjoiY2xhc2g2LnNzci1mcmVlLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2MTQiLCJhZGQiOiIxOTguNDEuMjEyLjE0IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2MTUiLCJhZGQiOiIxODUuMTYyLjIyOC4xMTAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImM1YTJkN2I4LWJmODQtNGY5Ny04NTc3LWI5Yjg3ZjJiYWFmNyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQVVJS044QVUiLCJob3N0Ijoib3BsZzEuY2ZjZG4yLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggW1ZNZXNzXSDwn4e68J+HsiBVU+OAkOS7mOi0ueaOqOiNkO+8mmh0dHBzLy90dC5zYnMvdmlw44CRIDIiLCJhZGQiOiIxNzIuNjcuMTM1LjU1IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzAyMDIwODAiLCJhZGQiOiIxNzIuNjcuNDYuMTMxIiwicG9ydCI6IjIwODIiLCJ0eXBlIjoibm9uZSIsImlkIjoiMDgyMTIyYTItODQ3OS00MDg5LTgyZjAtZjMyYmE1ZmM1NDI2IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9iYiIsImhvc3QiOiJoYW8uaHVhcWlhbi5pY3UiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xMUNETiIsImFkZCI6IjE0MS4xMDEuMTE0LjMxIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI1NmEyMTg4Yi0yYWI3LTQwMmMtYjliOC0zNDg0N2ZkZjA5NTgiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzVRTlJPU1JWIiwiaG9zdCI6Im9wbGcxLnpodWppY24yLmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggVVMoQXphZE5ldC50Lm1lKSg0NCkiLCJhZGQiOiI1MS44MS4yMjAuMTk1IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjZmZWExNjQ5LTQyNWItNDA5Mi1iZjUzLTI5NzkyMTUyYzkyNSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvc3Noa2l0L1Zhcml1ODgvNjM0ZGFiN2FiYWRmMS8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xM0NETiIsImFkZCI6IjE5MC45My4yNDUuMyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJvcGxnMS56aHVqaWNuMi5jb20iLCJ0bHMiOiJ0bHMifQ==
    ss://YWVzLTI1Ni1nY206ZmFCQW9ENTRrODdVSkc3@38.121.43.65:2375#%F0%9F%87%BA%F0%9F%87%B8%20US%28AzadNet.t.me%29%28168%29
    ss://YWVzLTI1Ni1nY206Y2RCSURWNDJEQ3duZklO@38.121.43.204:8119#%F0%9F%87%BA%F0%9F%87%B8%20US%28AzadNet.t.me%29%28225%29
    ss://YWVzLTI1Ni1nY206ZTRGQ1dyZ3BramkzUVk@38.75.136.34:9101#%F0%9F%87%BA%F0%9F%87%B8%20US%28AzadNet.t.me%29%28190%29
    ss://YWVzLTI1Ni1nY206ZmFCQW9ENTRrODdVSkc3@167.88.63.82:2376#%F0%9F%87%BA%F0%9F%87%B8%20US%28AzadNet.t.me%29%28176%29
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@38.86.135.27:6379#%F0%9F%87%BA%F0%9F%87%B8%20US%28AzadNet.t.me%29%2857%29
    ss://YWVzLTI1Ni1nY206a0RXdlhZWm9UQmNHa0M0@38.86.135.36:8882#%F0%9F%87%BA%F0%9F%87%B8%20US%28AzadNet.t.me%29%2888%29
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@38.91.106.75:3389#%F0%9F%87%BA%F0%9F%87%B8%20US%28AzadNet.t.me%29%28237%29
    ss://YWVzLTI1Ni1nY206ZmFCQW9ENTRrODdVSkc3@167.88.61.119:2376#%F0%9F%87%BA%F0%9F%87%B8%20US%28AzadNet.t.me%29%28184%29
    ss://YWVzLTI1Ni1nY206ZmFCQW9ENTRrODdVSkc3@142.202.48.7:2376#US_142
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2NSIsImFkZCI6IjIwMy4zMC4xOTEuNiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2NyIsImFkZCI6IjIwMy4zMC4xOTEuNCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi5pyq55+lXzAyMDIxMzMxIiwiYWRkIjoiMTYyLjE1OS4xMzcuMiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS0xMkNETiIsImFkZCI6IjE5MC45My4yNDQuMiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNDBkNDk2YTYtY2VlYi00MDk2LWJhZWItNGNjNTJiMjA1NjIxIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9FQ1RDSjBERiIsImhvc3QiOiJsZzEudHJ1bXAyMDIzLnVzIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC04IiwiYWRkIjoiMjMuMjI3LjM4LjIxIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC03IiwiYWRkIjoiMjMuMjI3LjM4LjIyIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS0xMENETiIsImFkZCI6IjE0MS4xMDEuMTE1LjMwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0MGQ0OTZhNi1jZWViLTQwOTYtYmFlYi00Y2M1MmIyMDU2MjEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0VDVENKMERGIiwiaG9zdCI6ImxnMS50cnVtcDIwMjMudXMiLCJ0bHMiOiJ0bHMifQ==
    trojan://cf4295378e209e70d12c5bdd017144dfd1c772d3@3-249-129-98.ipv4.rush.ml:8443?allowInsecure=0#IE_3.249.129.98_01262023c7ab-515trojan
    vmess://eyJ2IjoiMiIsInBzIjoiQ05feW91dHViZUDotYTmupDliIbkuqvluIhfMTQxIiwiYWRkIjoiY2xvdWRmbGFyZS5xdWVzdCIsInBvcnQiOiIyMDg2IiwidHlwZSI6Im5vbmUiLCJpZCI6IjgzM2RlOWQyLTk4YzUtNGFjNS05ZDMwLWUzYTdhZDkyOWQxMCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvYXJpZXMiLCJob3N0IjoiYnV5dm0uY2xvdWRmbGFyZS5xdWVzdCIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrPCfh6cg6Iux5Zu9XzAyMDIwNjUiLCJhZGQiOiIxMDMuMTA1LjUwLjE4OCIsInBvcnQiOiIxNjUzNiIsInR5cGUiOiJub25lIiwiaWQiOiI5MGQ2NDA0My02Y2U5LTQ0MDItZjJhYi1iMWE0YTVkMGQ5MDEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2JiIiwiaG9zdCI6IiIsInRscyI6IiJ9
    trojan://origin@188.40.250.247:443?allowInsecure=1#DE_188.40.250.247_01312023dd05-47trojan
    vmess://eyJ2IjoiMiIsInBzIjoiU0UoQXphZE5ldC50Lm1lKSIsImFkZCI6IjE4NS4yMjMuMjM1LjI5IiwicG9ydCI6IjU1ODcyIiwidHlwZSI6Im5vbmUiLCJpZCI6ImFiZjI5ODQ4LTZmZjgtNGE2MC1hYmUxLTZlMjI2NjE3NGRmZCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xQ0ROIiwiYWRkIjoiMjAzLjMwLjE5MS4xOTMiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjE3YjJhMzEzLTM3YTAtNDk0NS1hOGU0LWU2MzM3NTUwNmI0YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQTJESk9QRlQiLCJob3N0IjoibGcxMC5jZmNkbjEueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HpvCfh7ogZ2l0aHViLmNvbS9mcmVlZnEgLSDmvrPlpKfliKnkupogIDQzIiwiYWRkIjoianAtYW1kMS4wMTg5OTkueHl6IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI2NWU2MTllNy0wYmYxLTRmNWItYTM5MC01NzM1YjAxYTM3MTMiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzY1ZTYxOWU3LTBiZjEtNGY1Yi1hMzkwLTU3MzViMDFhMzcxMyIsImhvc3QiOiJqcC1hbWQxLjAxODk5OS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HpvCfh7ogQVUoQXphZE5ldC50Lm1lKSgxKSIsImFkZCI6InZhdTEuMGJhZC5jb20iLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjkyNzA5NGQzLWQ2NzgtNDc2My04NTkxLWUyNDBkMGJjYWU4NyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvY2hhdCIsImhvc3QiOiJ2YXUxLjBiYWQuY29tIiwidGxzIjoidGxzIn0=
    trojan://e8c1ab3c-89b3-4933-92df-682e6dce7819@152.67.98.30:443?allowInsecure=1#%F0%9F%87%A6%F0%9F%87%BA%20AU%28AzadNet.t.me%29%283%29
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoKSAxMDEiLCJhZGQiOiIxNTIuNjkuMTk3LjYwIiwicG9ydCI6IjEwNjkiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWM4ZTI2ZmUtODE1MC00YjYwLWFlNjQtODJmYzc3ZWJhMmNmIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hu/Cfh7Mg6LaK5Y2XXzAyMDIwMDUiLCJhZGQiOiIxMDMuMTc4LjIzNC4yMDEiLCJwb3J0IjoiNDE3ODUiLCJ0eXBlIjoibm9uZSIsImlkIjoiY2U2ZTgwNGUtMzI1OC00Y2MxLWE5MjItMWM4N2EzODg2NjExIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xNENETiIsImFkZCI6IjE5MC45My4yNDYuNCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7og5YyI54mZ5YipIDAwMSIsImFkZCI6IjE4NS4yMjUuNjkuMTM0IiwicG9ydCI6IjQ1MDgxIiwidHlwZSI6Im5vbmUiLCJpZCI6IjNjM2JmZDc1LWRjMzAtNGU3Ni04OTQwLTQ3ZTExMzdlMjFmOSIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6ImxnMTAuY2ZjZG4xLnh5eiIsInRscyI6IiJ9
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@109.169.72.249:809#AE%28AzadNet.t.me%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xNUNETiIsImFkZCI6IjE5MC45My4yNDUuNCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrvCfh6kg5Y2w5bqm5bC86KW/5LqaXzAyMDIwMDEiLCJhZGQiOiIxMDMuMTAyLjE1NC4xMDAiLCJwb3J0IjoiNTE0MjgiLCJ0eXBlIjoibm9uZSIsImlkIjoiNDljMWEzOWYtMjI4NC00NzlmLWY3NmItMGJhYmRmZjRiYzdlIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvQTJESk9QRlQiLCJob3N0IjoibGcxMC5jZmNkbjEueHl6IiwidGxzIjoiIn0=
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@167.88.61.175:8080#%E8%BF%99%E4%BA%9B%E8%8A%82%E7%82%B9%E5%8F%AA%E8%83%BD%E5%A4%87%E7%94%A8%E6%88%96%E8%80%85%E9%98%B2%E6%AD%A2%E5%A4%B1%E8%81%94%EF%BC%8C%E8%99%BD%E7%84%B6%E8%B4%A8%E9%87%8F%E5%B9%B6%E4%B8%8D%E6%98%AF%E5%BE%88%E5%A5%BD%EF%BC%8C%E4%B9%9F%E8%AF%B7%E4%BD%8E%E8%B0%83%E4%BD%BF%E7%94%A8%29%2017
    

</details>

### 所有节点
合并节点总数: `1039`
[节点链接](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [pojiezhiyuanjun/freev2](https://github.com/pojiezhiyuanjun/freev2), 节点数量: `119`
- [Alvin9999/pac2](https://github.com/Alvin9999/pac2), 节点数量: `100`
- [xiyaowong/freeFQ](https://github.com/xiyaowong/freeFQ), 节点数量: `156`
- [freefq/free](https://github.com/freefq/free), 节点数量: `50`
- [learnhard-cn/free_proxy_ss](https://github.com/learnhard-cn/free_proxy_ss), 节点数量: `9`
- [vpei/Free-Node-Merge](https://github.com/vpei/Free-Node-Merge), 节点数量: `1`
- [colatiger/v2ray-nodes](https://github.com/colatiger/v2ray-nodes), 节点数量: `70`
- [AzadNetCH/Clash](https://github.com/AzadNetCH/Clash), 节点数量: `3333`
- [ssrsub/ssr](https://github.com/ssrsub/ssr), 节点数量: `213`
- [Leon406/SubCrawler](https://github.com/Leon406/SubCrawler), 节点数量: `288`
- [yu-steven/openit](https://github.com/yu-steven/openit), 节点数量: `1`
- [Jsnzkpg/Jsnzkpg](https://github.com/Jsnzkpg/Jsnzkpg), 节点数量: `49`
- [ermaozi/get_subscribe](https://github.com/ermaozi/get_subscribe), 节点数量: `47`
- [gfwglass 节点池](https://gfwglass.tk), 节点数量: `1`
- [Meteor-1337/Meteor](https://github.com/Meteor-1337/Meteor), 节点数量: `1`
- [ronghuaxueleng/get_v2](https://github.com/ronghuaxueleng/get_v2), 节点数量: `46`
- [anaer/Sub](https://github.com/anaer/Sub), 节点数量: `268`
- [xrayfree/free-ssr-ss-v2ray-vpn-clash](https://github.com/xrayfree/free-ssr-ss-v2ray-vpn-clash), 节点数量: `70`
- [aiboboxx/v2rayfree](https://github.com/aiboboxx/v2rayfree), 节点数量: `39`
- [Pawdroid/Free-servers](https://github.com/Pawdroid/Free-servers), 节点数量: `13`
- [kxswa/k](https://github.com/kxswa/k), 节点数量: `24`
- [Nodefree.org](https://github.com/Fukki-Z/nodefree), 节点数量: `50`
- [Rokate/Proxy-Sub](https://github.com/Rokate/Proxy-Sub), 节点数量: `2629`
- [mianfeifq/share](https://github.com/mianfeifq/share), 节点数量: `249`
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
