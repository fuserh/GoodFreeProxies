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

    trojan://be28dfd8-211a-4475-a078-813d30e22ad1@edge02.themars.top:31103?allowInsecure=1#%E5%85%8D%E8%B4%B9%E8%8A%82%E7%82%B9-JP02
    trojan://da777aae-defb-41d0-a183-2c27da2b4677@150.230.96.103:443?allowInsecure=1&sni=150.230.96.103#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2810%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgSlAoaHR0cHMvL2F3a2ouY2Yva3kg5rOo5YaM5L2T6aqM5rWB5aqS5L2T5py65Zy6KXlvdXR1YmXpmL/kvJ/np5HmioAgMiIsImFkZCI6ImpwLWFtZDEuMDE4OTk5Lnh5eiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNjVlNjE5ZTctMGJmMS00ZjViLWEzOTAtNTczNWIwMWEzNzEzIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii82NWU2MTllNy0wYmYxLTRmNWItYTM5MC01NzM1YjAxYTM3MTMiLCJob3N0IjoianAtYW1kMS4wMTg5OTkueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgSlAoaHR0cHMvL2F3a2ouY2Yva3kg5rOo5YaM5L2T6aqM5rWB5aqS5L2T5py65Zy6KXlvdXR1YmXpmL/kvJ/np5HmioAgMyIsImFkZCI6ImpwLWFtZDIuMDE4OTk5Lnh5eiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYTc5ZjIxMjctM2JhNC00YWY4LTk2ZDUtMmRiM2EwZTE4NmE3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9hNzlmMjEyNy0zYmE0LTRhZjgtOTZkNS0yZGIzYTBlMTg2YTciLCJob3N0IjoianAtYW1kMi4wMTg5OTkueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cgS1IoaHR0cHMvL2F3a2ouY2Yva3kg5rOo5YaM5L2T6aqM5rWB5aqS5L2T5py65Zy6KXlvdXR1YmXpmL/kvJ/np5HmioAgMyIsImFkZCI6ImtyLWFybTEuMDE4OTk5Lnh5eiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTY0N2RmMmUtYmIwYy00YzBjLWFlMDMtMmRlMWI0OTQzNDhkIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81NjQ3ZGYyZS1iYjBjLTRjMGMtYWUwMy0yZGUxYjQ5NDM0OGQiLCJob3N0Ijoia3ItYXJtMS4wMTg5OTkueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cgS1IoQXphZE5ldC50Lm1lKSIsImFkZCI6IjE1Mi42Ny4yMTguMzgiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImI1ZTk0ODBhLWI3YWEtNDBhNC1mOWE3LTUyOTliNWUzNjNiNCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgQXNpYSDpppnmuK8wNCB8IOebtOi/niB8IDEuMHggfCBWMSAtIOmFuOWltlZQTiIsImFkZCI6IjIwLjI0Ny4xMTIuMTI1IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjBhNDFjNWY4LTRmNTgtM2M1Yi05MzNmLTEyY2YzZjg1MGQwMSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvbnkiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgU0coaHR0cHMvL2F3a2ouY2Yva3kg5rOo5YaM5L2T6aqM5rWB5aqS5L2T5py65Zy6KXlvdXR1YmXpmL/kvJ/np5HmioAiLCJhZGQiOiJzZy0xLjAxODk5OS54eXoiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjM4NGQzOGE5LWM4ZTQtNGEyNy1lNDllLTcyNDU0Yzc5OGQ4NSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvMzg0ZDM4YTktYzhlNC00YTI3LWU0OWUtNzI0NTRjNzk4ZDg1IiwiaG9zdCI6InNnLTEuMDE4OTk5Lnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgU0coQXphZE5ldC50Lm1lKSg1KSIsImFkZCI6IjE3Mi4xMDQuMTY3LjI0MCIsInBvcnQiOiI3MjA0IiwidHlwZSI6Im5vbmUiLCJpZCI6IjljNTI3NzZiLTRiMDEtNGFlNi05ZjdkLTI1Y2Q0NzI1ZTEzYyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvc2cxIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cgX0tSX+mfqeWbvV8yIiwiYWRkIjoiNDMuMjAxLjkuODIiLCJwb3J0IjoiMjg5MTEiLCJ0eXBlIjoibm9uZSIsImlkIjoiMGZmNTkyYmUtMTA4Yi00OTE4LWMxYzItY2E3M2NmNzEwNzAwIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvc2cxIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzAxMzEwMjUiLCJhZGQiOiI0My4xMzQuMTc3LjEzMCIsInBvcnQiOiIyNzgwMyIsInR5cGUiOiJub25lIiwiaWQiOiI0Mjc3OWU3MS0yZTZiLTRlYjQtOWY0My1kZTRlNTdiYjhiMmIiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9zZzEiLCJob3N0IjoiIiwidGxzIjoiIn0=
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@85.208.108.93:6379#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2817%29
    ss://YWVzLTI1Ni1nY206cEtFVzhKUEJ5VFZUTHRN@85.208.108.18:443#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2827%29
    ss://YWVzLTI1Ni1nY206Y2RCSURWNDJEQ3duZklO@85.208.108.19:8118#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2879%29
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@85.208.108.60:6379#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2818%29
    ss://YWVzLTI1Ni1nY206cEtFVzhKUEJ5VFZUTHRN@85.208.108.94:4444#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2822%29
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@85.208.108.22:8888#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2897%29
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@85.208.108.59:6379#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2819%29
    ss://YWVzLTI1Ni1nY206ZTRGQ1dyZ3BramkzUVk@85.208.108.58:9101#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2864%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgU0coQXphZE5ldC50Lm1lKSgxMSkiLCJhZGQiOiIxMTguMTA3LjU3LjE4MCIsInBvcnQiOiIyNzU0MiIsInR5cGUiOiJub25lIiwiaWQiOiIwYzg4YjVmZS1iMTliLTRiMTctOWFiYi05OWEwODI0ZDA0ZjEiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9zZzEiLCJob3N0IjoiIiwidGxzIjoiIn0=
    ss://YWVzLTI1Ni1jZmI6ZUlXMERuazY5NDU0ZTZuU3d1c3B2OURtUzIwMXRRMEQ@139.162.41.174:8099#SG_127
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpYczlPUlQ0ajY1YjhIcmVacmcwcA@185.160.26.91:1664#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%28171%29
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@85.208.108.20:6379#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2821%29
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@54.254.147.251:804#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29%2821%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzAxMzEwMjEiLCJhZGQiOiIxMzguMi43OC4xOTIiLCJwb3J0IjoiMTA1MTIiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTg3ODFlZWUtYmFiYS02NjY2LWJhYmEtMmNhMGFkYTY1NjhiIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvc2cxIiwiaG9zdCI6IiIsInRscyI6IiJ9
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@85.208.108.21:6379#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2820%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgX1VTX+e+juWbvS0+8J+Hr/Cfh7VfSlBf5pel5pysIiwiYWRkIjoibWluZzIua2l3aXJlaWNoLmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMThlNWY0MGYtYmRhNi00YzE1LTkzMzQtZTg3Y2RhNjA0N2FmIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9yYXkiLCJob3N0IjoibWluZzIua2l3aXJlaWNoLmNvbSIsInRscyI6InRscyJ9
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@81.90.189.41:810#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29%2818%29
    vmess://eyJ2IjoiMiIsInBzIjoiVFdfMTAzLjEzMS4xODkuMjEyXzAyMDEyMDIzZTVmZS0xOTc0dm1lc3MiLCJhZGQiOiIxMDMuMTMxLjE4OS4yMTIiLCJwb3J0IjoiNTY5NjciLCJ0eXBlIjoibm9uZSIsImlkIjoiODExMGViZDItNWFiOC00ZGZjLTg3NzYtOTRiYzM3N2M2YmU2IiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvcmF5IiwiaG9zdCI6Im1pbmcyLmtpd2lyZWljaC5jb20iLCJ0bHMiOiIifQ==
    trojan://0c6a3341e8d5ab17@103.172.116.196:3389?allowInsecure=1#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29%2814%29
    trojan://6d64570c-81d4-30fa-b2e2-dce73e1a2702@138.2.45.89:44301?allowInsecure=1&sni=osav101.jd0001.top#%F0%9F%87%AF%F0%9F%87%B5%20%5BTrojan%5D%20%F0%9F%87%AF%F0%9F%87%B5%20JP%E3%80%90%E4%BB%98%E8%B4%B9%E6%8E%A8%E8%8D%90%EF%BC%9Ahttps%2F%2Ftt.sbs%2Fvip%E3%80%91
    trojan://b291d129-ee55-4801-a9b8-b5316e5c37b7@138.2.113.84:443?allowInsecure=1#%F0%9F%87%B0%F0%9F%87%B7%20KR%28AzadNet.t.me%29%284%29
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@148.66.56.99:812#%F0%9F%87%AD%F0%9F%87%B0%20HK%28AzadNet.t.me%29%289%29
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@13.215.49.89:443#%F0%9F%87%B8%F0%9F%87%AC%20_SG_%E6%96%B0%E5%8A%A0%E5%9D%A1_3%202
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cg6Z+p5Zu9XzAxMzEwMTIiLCJhZGQiOiIzLjM1LjEzNC4yMCIsInBvcnQiOiI0NDYyOCIsInR5cGUiOiJub25lIiwiaWQiOiI4ZWM3OGY1NC0wNTFiLTRhZjAtODMyNC0wZDkyNWM3NGM1ZTAiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgSEsoQXphZE5ldC50Lm1lKSg0KSIsImFkZCI6IjQzLjE1NC4zNC40OSIsInBvcnQiOiIyMzE4MyIsInR5cGUiOiJub25lIiwiaWQiOiJiNDAyYTRhZi0yODVhLTQ2M2UtYzNhNy01M2Y5MWVmZGVjNzgiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    trojan://cd27884b-c5af-34ec-b75f-8248077818fe@a.xg.hk.cat77.cloud:5687?allowInsecure=0#HK_youtube%40%E8%B5%84%E6%BA%90%E5%88%86%E4%BA%AB%E5%B8%88_104
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgZ2l0aHViLmNvbS9mcmVlZnEgLSDml6XmnKzkuJzkuqxMaW5vZGXmlbDmja7kuK3lv4MgNDQiLCJhZGQiOiIxNzIuMTA0LjEyMi4yMSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiOTI3MDk0ZDMtZDY3OC00NzYzLTg1OTEtZTI0MGQwYmNhZTg3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgSlAoQXphZE5ldC50Lm1lKSIsImFkZCI6IjE3Mi4xMDUuMjIwLjEwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI5MjcwOTRkMy1kNjc4LTQ3NjMtODU5MS1lMjQwZDBiY2FlODciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2NoYXQiLCJob3N0IjoiIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgSlAoQXphZE5ldC50Lm1lKSgzKSIsImFkZCI6IjE2OC4xMzguMjA2LjE0MSIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiJhZDA1ZTAxZi1jMmMwLTQxZGEtZTc5Yy1mZjY4MjM3MzE3ZjciLCJhaWQiOiIwIiwibmV0IjoiaHR0cCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgSlAoQXphZE5ldC50Lm1lKSg0KSIsImFkZCI6IjE2OC4xMzguMTk0LjI0MyIsInBvcnQiOiIzMzQyMSIsInR5cGUiOiJub25lIiwiaWQiOiI5NGU1NmZmOS1jY2YxLTQxNGUtYTExNC00NmUwYTc5ZjY2MTQiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    trojan://11a4e5be-3c87-37d2-aac8-00b85ef0fcdc@20.187.108.142:32154?allowInsecure=1&sni=relay-hk-az.fib-sys.cyou#%F0%9F%87%AD%F0%9F%87%B0%20HK%28AzadNet.t.me%29%288%29
    ss://YWVzLTI1Ni1nY206ZmFCQW9ENTRrODdVSkc3@85.208.108.90:2376#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2850%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgZ2l0aHViLmNvbS9mcmVlZnEgLSDml6XmnKzkuJzkuqxMaW5vZGXmlbDmja7kuK3lv4MgMSIsImFkZCI6InY2LjU4MzE4MS54eXoiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTYxZDk1MzMtZTIwYS00ZmYwLTgzZDQtODBkMGNjNTg4ZGZiIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoidjYuNTgzMTgxLnh5eiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggVVMoQXphZE5ldC50Lm1lKSgxMCkiLCJhZGQiOiIyMy4xMDUuMTk5LjE2MCIsInBvcnQiOiIyMzE2NiIsInR5cGUiOiJub25lIiwiaWQiOiJmMWNkYTlkYS1jODU5LTRmMjYtZjYwOS1hMmU4ODM3Y2M5YjgiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoidjYuNTgzMTgxLnh5eiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggVVMoQXphZE5ldC50Lm1lKSg0MykiLCJhZGQiOiI1NC4xNDkuNzUuOTEiLCJwb3J0IjoiNDI0NDAiLCJ0eXBlIjoibm9uZSIsImlkIjoiZGE4NDhkYjAtNzdkNy00MThhLWEwMmMtOWIwYzJmYWZlOTdhIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6InY2LjU4MzE4MS54eXoiLCJ0bHMiOiIifQ==
    trojan://a2c8194b-fcfd-4c39-a6bd-31ea9f4ea671@5.161.135.210:443?allowInsecure=1&sni=5.161.135.210#%F0%9F%87%BA%F0%9F%87%B8%20US%28AzadNet.t.me%29%2851%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh6Yg5Yqg5ou/5aSnIDAwMSIsImFkZCI6ImNhLWxzMDMubmIxLmZyIiwicG9ydCI6IjY0NDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImNiNzAwMWM3LWU0OTUtNDFhYy1iOTQyLWYyNWY2MDUyMzQxNCIsImFpZCI6IjEiLCJuZXQiOiJ3cyIsInBhdGgiOiIvY2xpZW50YXJlYSIsImhvc3QiOiJjYS1sczAzLm5iMS5mciIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71DbG91ZEZsYXJl6IqC54K5IDQ4IiwiYWRkIjoiMTcyLjY3LjIwMS4xNCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71DbG91ZEZsYXJl6IqC54K5IDM0IiwiYWRkIjoiMTcyLjY3LjEyNy4yNTAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjJiMjE0MTIyLTE5MDYtNDI4YS1iYmI3LWEwMzljYmI3Y2Q1YyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvOUpaRkRUS0UiLCJob3N0IjoiZnIxLnRydW1wMjAyMy5vcmciLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS0xMUNETiIsImFkZCI6IjE0MS4xMDEuMTE0LjMwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0MGQ0OTZhNi1jZWViLTQwOTYtYmFlYi00Y2M1MmIyMDU2MjEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0VDVENKMERGIiwiaG9zdCI6ImxnMS50cnVtcDIwMjMudXMiLCJ0bHMiOiJ0bHMifQ==
    trojan://0c355515-b1e5-4c0a-b843-e1defbe7c0fa@trfg.ballistics.top:443?allowInsecure=0#%F0%9F%87%BA%F0%9F%87%B8%20github.com%2Ffreefq%20-%20%E7%BE%8E%E5%9B%BD%E5%8A%A0%E5%88%A9%E7%A6%8F%E5%B0%BC%E4%BA%9A%E5%B7%9EWinnetka%2017
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggW1ZNZXNzXSDwn4e68J+HsiBVU+OAkOS7mOi0ueaOqOiNkO+8mmh0dHBzLy90dC5zYnMvdmlw44CRIDMiLCJhZGQiOiJ3dnZ3dy5jb20iLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImM1YTJkN2I4LWJmODQtNGY5Ny04NTc3LWI5Yjg3ZjJiYWFmNyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQVVJS044QVUiLCJob3N0Ijoib3BsZzEuY2ZjZG4yLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDAzMyIsImFkZCI6ImRlLWxzMDMubmIxLmZyIiwicG9ydCI6IjY0NDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImNiNzAwMWM3LWU0OTUtNDFhYy1iOTQyLWYyNWY2MDUyMzQxNCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvY2xpZW50YXJlYSIsImhvc3QiOiJkZS1sczAzLm5iMS5mciIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2MSIsImFkZCI6IjIwMy4zMC4xODguMTIxIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggW1ZNZXNzXSDwn4e68J+HsiBVU+OAkOS7mOi0ueaOqOiNkO+8mmh0dHBzLy90dC5zYnMvdmlw44CRIDEyIiwiYWRkIjoiMTcyLjY3LjEzNS41NSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggW1ZNZXNzXSDwn4e68J+HsiBVU+OAkOS7mOi0ueaOqOiNkO+8mmh0dHBzLy90dC5zYnMvdmlw44CRIDEwIiwiYWRkIjoib3ZoLTMuNTU1NTMwLnh5eiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My02Q0ROIiwiYWRkIjoiMjAzLjMwLjE4OC4xOTAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjE3YjJhMzEzLTM3YTAtNDk0NS1hOGU0LWU2MzM3NTUwNmI0YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQTJESk9QRlQiLCJob3N0IjoibGcxMC5jZmNkbjEueHl6IiwidGxzIjoidGxzIn0=
    trojan://0c355515-b1e5-4c0a-b843-e1defbe7c0fa@trxn.ballistics.top:443?allowInsecure=0#%F0%9F%87%BA%F0%9F%87%B8%20github.com%2Ffreefq%20-%20%E7%BE%8E%E5%9B%BD%20%2043
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDAwOCIsImFkZCI6ImZiaS5nb3YiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImQ1YTM4ZWFmLWI3MjMtNDViZS1iN2QyLTNjNGU0NWIyOTQwMCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvdmlkZW9zIiwiaG9zdCI6ImhrMTIudGFyZ29vY2xvdWQubGl2ZSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2MTQiLCJhZGQiOiIxOTguNDEuMjEyLjE0IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzAxMzEzMTIiLCJhZGQiOiIxNzIuNjcuNDUuMTQ0IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC0xMyIsImFkZCI6IjE4NS4xNjIuMjI4LjIyOSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC0xMSIsImFkZCI6IjIzLjIyNy4zOC4yNiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC0xNSIsImFkZCI6IjIzLjIyNy4zOC4zOCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0zQ0ROIiwiYWRkIjoiMjMuMjI3LjM4LjM5IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI1NmEyMTg4Yi0yYWI3LTQwMmMtYjliOC0zNDg0N2ZkZjA5NTgiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzVRTlJPU1JWIiwiaG9zdCI6Im9wbGcxLnpodWppY24yLmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2MjAiLCJhZGQiOiIyMDMuMzAuMTkxLjgiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImM1YTJkN2I4LWJmODQtNGY5Ny04NTc3LWI5Yjg3ZjJiYWFmNyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQVVJS044QVUiLCJob3N0Ijoib3BsZzEuY2ZjZG4yLnh5eiIsInRscyI6InRscyJ9
    trojan://0c355515-b1e5-4c0a-b843-e1defbe7c0fa@trny.ballistics.top:443?allowInsecure=1#%F0%9F%87%A9%F0%9F%87%AA%20%E5%BE%B7%E5%9B%BD%20001
    vmess://eyJ2IjoiMiIsInBzIjoifDEwLjE2TWIiLCJhZGQiOiIxMDQuMTcuMjI2LjU1IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjczNWZmNDMwLTlkMWEtNGY1Ny1mYjY2LWU0M2EyNmE3NmY3MCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvY2NwcCIsImhvc3QiOiJjY3BwLjkxcGFuLm9uZSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoidGfpopHpgZNAc2hhcmluZ25vZGUgOSIsImFkZCI6IjEwNC4yNi4xNC41MyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoifDE1LjYwTWIiLCJhZGQiOiIxNzMuMjQ1LjU4LjI0MCIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI3MzVmZjQzMC05ZDFhLTRmNTctZmI2Ni1lNDNhMjZhNzZmNzAiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2NjcHAiLCJob3N0IjoiY2NwcC45MXBhbi5vbmUiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoifCA2LjE1TWIiLCJhZGQiOiIxMDQuMTkuMjA0LjExNSIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI3MzVmZjQzMC05ZDFhLTRmNTctZmI2Ni1lNDNhMjZhNzZmNzAiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2NjcHAiLCJob3N0IjoiY2NwcC45MXBhbi5vbmUiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2MTQgMiIsImFkZCI6IjE5OC40MS4yMTIuMTQiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImM1YTJkN2I4LWJmODQtNGY5Ny04NTc3LWI5Yjg3ZjJiYWFmNyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQVVJS044QVUiLCJob3N0Ijoib3BsZzEuY2ZjZG4yLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS0xMkNETiIsImFkZCI6IjE5MC45My4yNDQuMiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNDBkNDk2YTYtY2VlYi00MDk2LWJhZWItNGNjNTJiMjA1NjIxIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9FQ1RDSjBERiIsImhvc3QiOiJsZzEudHJ1bXAyMDIzLnVzIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS0xMENETiIsImFkZCI6IjE0MS4xMDEuMTE1LjMwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0MGQ0OTZhNi1jZWViLTQwOTYtYmFlYi00Y2M1MmIyMDU2MjEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0VDVENKMERGIiwiaG9zdCI6ImxnMS50cnVtcDIwMjMudXMiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqfCfh6ogREUoQXphZE5ldC50Lm1lKSg1KSIsImFkZCI6Ijk0LjEzMC43OS4yMDkiLCJwb3J0IjoiMzA5NDEiLCJ0eXBlIjoibm9uZSIsImlkIjoiZWFmYzE4NWItYjAzZi00MDcwLThhNzYtZmZkOTg4MTM4MjQ5IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoifCAzLjkyTWIiLCJhZGQiOiIxNjIuMTU5LjcuODQiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiNzM1ZmY0MzAtOWQxYS00ZjU3LWZiNjYtZTQzYTI2YTc2ZjcwIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9jY3BwIiwiaG9zdCI6ImNjcHAuOTFwYW4ub25lIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC0xNSAyIiwiYWRkIjoiMjMuMjI3LjM4LjM4IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2MSAyIiwiYWRkIjoiMjAzLjMwLjE4OC4xMjEiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImM1YTJkN2I4LWJmODQtNGY5Ny04NTc3LWI5Yjg3ZjJiYWFmNyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQVVJS044QVUiLCJob3N0Ijoib3BsZzEuY2ZjZG4yLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2MTUiLCJhZGQiOiIxODUuMTYyLjIyOC4xMTAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImM1YTJkN2I4LWJmODQtNGY5Ny04NTc3LWI5Yjg3ZjJiYWFmNyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQVVJS044QVUiLCJob3N0Ijoib3BsZzEuY2ZjZG4yLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC0xNyIsImFkZCI6IjE5OC40MS4yMTIuMTIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImM1YTJkN2I4LWJmODQtNGY5Ny04NTc3LWI5Yjg3ZjJiYWFmNyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQVVJS044QVUiLCJob3N0Ijoib3BsZzEuY2ZjZG4yLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoifDY5Ljg0TWIiLCJhZGQiOiJmYmkuZ292IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJkNWEzOGVhZi1iNzIzLTQ1YmUtYjdkMi0zYzRlNDViMjk0MDAiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3ZpZGVvcyIsImhvc3QiOiJoazEyLnRhcmdvb2Nsb3VkLmxpdmUiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2MjAgMiIsImFkZCI6IjIwMy4zMC4xOTEuOCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    trojan://cb43b7c2-b744-41c5-bcc2-fd7467b332cf@140.238.205.173:443?allowInsecure=1#%F0%9F%87%A6%F0%9F%87%BA%20AU%28AzadNet.t.me%29%285%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2NiIsImFkZCI6IjIwMy4zMC4xOTEuNSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS00Q0ROIiwiYWRkIjoiMjAzLjMwLjE5MC4xOTAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQwZDQ5NmE2LWNlZWItNDA5Ni1iYWViLTRjYzUyYjIwNTYyMSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvRUNUQ0owREYiLCJob3N0IjoibGcxLnRydW1wMjAyMy51cyIsInRscyI6InRscyJ9
    trojan://origin@176.31.83.90:443?allowInsecure=1#%F0%9F%87%AB%F0%9F%87%B7%20FR%28AzadNet.t.me%29%281%29
    vmess://eyJ2IjoiMiIsInBzIjoifDExLjU2TWIiLCJhZGQiOiIxMDQuMTcuNjUuMjEzIiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjczNWZmNDMwLTlkMWEtNGY1Ny1mYjY2LWU0M2EyNmE3NmY3MCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvY2NwcCIsImhvc3QiOiJjY3BwLjkxcGFuLm9uZSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi00Q0ROIiwiYWRkIjoiMjAzLjMwLjE5MC4xOTEiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjU2YTIxODhiLTJhYjctNDAyYy1iOWI4LTM0ODQ3ZmRmMDk1OCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvNVFOUk9TUlYiLCJob3N0Ijoib3BsZzEuemh1amljbjIuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xNUNETiIsImFkZCI6IjE5MC45My4yNDUuNCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xQ0ROIiwiYWRkIjoiMjAzLjMwLjE5MS4xOTMiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjE3YjJhMzEzLTM3YTAtNDk0NS1hOGU0LWU2MzM3NTUwNmI0YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQTJESk9QRlQiLCJob3N0IjoibGcxMC5jZmNkbjEueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0yQ0ROIiwiYWRkIjoiMTg4LjExNC45OS4xMSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    

</details>

### 所有节点
合并节点总数: `980`
[节点链接](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [pojiezhiyuanjun/freev2](https://github.com/pojiezhiyuanjun/freev2), 节点数量: `131`
- [Alvin9999/pac2](https://github.com/Alvin9999/pac2), 节点数量: `100`
- [xiyaowong/freeFQ](https://github.com/xiyaowong/freeFQ), 节点数量: `156`
- [freefq/free](https://github.com/freefq/free), 节点数量: `66`
- [learnhard-cn/free_proxy_ss](https://github.com/learnhard-cn/free_proxy_ss), 节点数量: `9`
- [vpei/Free-Node-Merge](https://github.com/vpei/Free-Node-Merge), 节点数量: `1`
- [colatiger/v2ray-nodes](https://github.com/colatiger/v2ray-nodes), 节点数量: `85`
- [AzadNetCH/Clash](https://github.com/AzadNetCH/Clash), 节点数量: `3333`
- [ssrsub/ssr](https://github.com/ssrsub/ssr), 节点数量: `213`
- [Leon406/SubCrawler](https://github.com/Leon406/SubCrawler), 节点数量: `242`
- [yu-steven/openit](https://github.com/yu-steven/openit), 节点数量: `1`
- [Jsnzkpg/Jsnzkpg](https://github.com/Jsnzkpg/Jsnzkpg), 节点数量: `49`
- [ermaozi/get_subscribe](https://github.com/ermaozi/get_subscribe), 节点数量: `47`
- [gfwglass 节点池](https://gfwglass.tk), 节点数量: `1`
- [Meteor-1337/Meteor](https://github.com/Meteor-1337/Meteor), 节点数量: `1`
- [ronghuaxueleng/get_v2](https://github.com/ronghuaxueleng/get_v2), 节点数量: `15`
- [anaer/Sub](https://github.com/anaer/Sub), 节点数量: `253`
- [xrayfree/free-ssr-ss-v2ray-vpn-clash](https://github.com/xrayfree/free-ssr-ss-v2ray-vpn-clash), 节点数量: `85`
- [aiboboxx/v2rayfree](https://github.com/aiboboxx/v2rayfree), 节点数量: `35`
- [Pawdroid/Free-servers](https://github.com/Pawdroid/Free-servers), 节点数量: `11`
- [kxswa/k](https://github.com/kxswa/k), 节点数量: `24`
- [Nodefree.org](https://github.com/Fukki-Z/nodefree), 节点数量: `50`
- [Rokate/Proxy-Sub](https://github.com/Rokate/Proxy-Sub), 节点数量: `2638`
- [mianfeifq/share](https://github.com/mianfeifq/share), 节点数量: `247`
- [peasoft/NoMoreWalls](https://github.com/peasoft/NoMoreWalls), 节点数量: `298`
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
