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

    vmess://eyJ2IjoiMiIsInBzIjoiSlBfQXphZE5ldCg2MSkiLCJhZGQiOiIxNjguMTM4LjIwNy42NiIsInBvcnQiOiIyMTM2NSIsInR5cGUiOiJub25lIiwiaWQiOiI5MDVmOTliMS1lN2JhLTQ1ZTAtYWU0ZC1iMGZmZGYwYWQyNDUiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiU0dfQXphZE5ldCgzMykiLCJhZGQiOiJ2c2cxLjBiYWQuY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI5MjcwOTRkMy1kNjc4LTQ3NjMtODU5MS1lMjQwZDBiY2FlODciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2NoYXQiLCJob3N0IjoidnNnMS4wYmFkLmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCg5KSIsImFkZCI6IjE4Mi4xNi4xLjE5NCIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiIwMGExZGExNC1kNTVmLTVmNzUtZTM0Ni03OWI5ODVlMWE3MjMiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL29wdC92aWRlby9pbWFnZXMiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzAxMTIwNzAiLCJhZGQiOiIxNS4yMzUuMTg0LjM2IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjdjZTUyNWY1LTNhOWItNDYyNy1hZTBlLTNjYTBiNTc1MTllMyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvdm1lc3MiLCJob3N0IjoiMTUuMjM1LjE4NC4zNiIsInRscyI6IiJ9
    ss://YWVzLTI1Ni1nY206UENubkg2U1FTbmZvUzI3@85.208.108.58:8090#JP_AzadNet%2823%29
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfMjAzLjIxOC41My4yMDdfMDExMjIwMjNkMDMzLTQxOHZtZXNzIiwiYWRkIjoiMjAzLjIxOC41My4yMDciLCJwb3J0IjoiMTgwMDEiLCJ0eXBlIjoibm9uZSIsImlkIjoiN2FmZmEzMjktNWUxNS0zNjllLTg5MjktYjY0NTJjZGYyNjE2IiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvdm1lc3MiLCJob3N0IjoiMTUuMjM1LjE4NC4zNiIsInRscyI6IiJ9
    trojan://0c6a3341e8d5ab17@103.172.116.196:3389?allowInsecure=1&sni=f5465c4.pg.gladns.com#SG_AzadNet%2835%29
    trojan://7118b5f4-0ea4-4c11-be7f-11471cb91e4a@144.24.72.126:443?allowInsecure=1#KR_AzadNet%289%29
    ss://YWVzLTI1Ni1nY206UENubkg2U1FTbmZvUzI3@85.208.108.18:8091#JP_AzadNet%2819%29
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@85.208.108.21:3306#JP_AzadNet%2870%29
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@85.208.108.22:8888#JP_AzadNet%2833%29
    ss://YWVzLTI1Ni1nY206Rm9PaUdsa0FBOXlQRUdQ@85.208.108.20:7306#JP_AzadNet%2816%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hKOayueeuoeegtOino+i1hOa6kOWQmykgNCIsImFkZCI6IjEzOS45OS40NS4xOTMiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiOTg5NTgxODUtOGIxYi00NzE4LTk1NzgtYTEzNDYwYzUzYjZmIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii92bWVzcyIsImhvc3QiOiIxMzkuOTkuNDUuMTkzIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7Ug5pel5pysIiwiYWRkIjoiMTAzLjE0MC4xMzYuMTY5IiwicG9ydCI6IjU1NTU1IiwidHlwZSI6Im5vbmUiLCJpZCI6IjFiZjJjYjcwLTlmZGUtNGI2MC04ZGY3LTI5ZTkzMmZkZjc2MyIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL3ZtZXNzIiwiaG9zdCI6IjEzOS45OS40NS4xOTMiLCJ0bHMiOiIifQ==
    ss://YWVzLTI1Ni1jZmI6ZUlXMERuazY5NDU0ZTZuU3d1c3B2OURtUzIwMXRRMEQ@139.162.5.19:8099#SG_AzadNet%2811%29
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@217.197.161.136:808#SG_AzadNet%2823%29
    trojan://b341f309-7e2b-45c4-a316-9e23037e3711@sg.liangyuandian.top:443?allowInsecure=1#HK_AzadNet%2824%29
    trojan://b42c2c42-b8ef-4cbe-8443-8870cf10875a@20.24.95.62:443?allowInsecure=1&sni=data-hk.efyunpan.com#HK_AzadNet%283%29
    trojan://b42c2c42-b8ef-4cbe-8443-8870cf10875a@20.247.106.224:443?allowInsecure=1&sni=data-tw.efyunpan.com#HK_AzadNet%284%29
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCg1KSIsImFkZCI6IjQ3LjI0Mi43OS4xNjciLCJwb3J0IjoiODQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjODJhYzMxNC0zZGFiLTNkYzYtOTQ4OC1hNTFiYWU4MTkwNjUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0Rvd25sb2FkIiwiaG9zdCI6IiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCg2KSIsImFkZCI6IjguMjE4LjU3LjMyIiwicG9ydCI6Ijg0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzgyYWMzMTQtM2RhYi0zZGM2LTk0ODgtYTUxYmFlODE5MDY1IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9Eb3dubG9hZCIsImhvc3QiOiIiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCg3KSIsImFkZCI6IjguMjE4LjcyLjIzOCIsInBvcnQiOiI4NDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImM4MmFjMzE0LTNkYWItM2RjNi05NDg4LWE1MWJhZTgxOTA2NSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvRG93bmxvYWQiLCJob3N0IjoiIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCg4KSIsImFkZCI6IjQ3LjI0My44OS4xNzciLCJwb3J0IjoiODQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjODJhYzMxNC0zZGFiLTNkYzYtOTQ4OC1hNTFiYWU4MTkwNjUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0Rvd25sb2FkIiwiaG9zdCI6IiIsInRscyI6InRscyJ9
    trojan://b42c2c42-b8ef-4cbe-8443-8870cf10875a@20.247.107.26:443?allowInsecure=1&sni=data-hk.efyunpan.com#HK_AzadNet%282%29
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgxMCkiLCJhZGQiOiIyMC4xODcuMTIyLjEzMiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYjc0NGY1Y2MtZWFiMi1kMmNkLWY0NzctNzY2NDZkMTc5ODdmIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9wZXRhbHZ3cyIsImhvc3QiOiIiLCJ0bHMiOiJ0bHMifQ==
    trojan://aef2ca33-b162-409f-8f16-4c736c338412@20.205.37.136:443?allowInsecure=1#HK_AzadNet%2811%29
    trojan://f8d19ba5-8684-45f2-8523-77dbea588955@ru.iamnotagoodman.com:443?allowInsecure=1#HK_AzadNet%2812%29
    trojan://459d23f4-dcfd-4fef-9ba3-ef0ad10fc336@vn.iamnotagoodman.com:443?allowInsecure=1#HK_AzadNet%2813%29
    trojan://459d23f4-dcfd-4fef-9ba3-ef0ad10fc336@usla.iamnotagoodman.com:443?allowInsecure=1#HK_AzadNet%2814%29
    trojan://1bf16b43-0ad5-4512-a0e8-34bb8966278e@ap.stablize.top:443?allowInsecure=1#HK_AzadNet%2815%29
    trojan://4f8c0e41-dbdb-40f1-99cb-2c2a0b909b52@ar.iamnotagoodman.com:443?allowInsecure=1#HK_AzadNet%2816%29
    trojan://1bf16b43-0ad5-4512-a0e8-34bb8966278e@de.stablize.top:443?allowInsecure=1#HK_AzadNet%2817%29
    trojan://28bccca2-43d2-47f8-bd63-b1361ce7d362@kh.iamnotagoodman.com:443?allowInsecure=1#HK_AzadNet%2818%29
    trojan://ceaea123-1b4b-469b-8358-bcd5f5529305@uk.liangyuandian.top:443?allowInsecure=1#HK_AzadNet%2819%29
    trojan://51c44c4e-f8c2-4419-a52b-b4b7bd915078@ca.liangyuandian.top:443?allowInsecure=1#HK_AzadNet%2820%29
    trojan://18304160-03d4-4c55-95c1-586c0a5f3a0a@jp.liangyuandian.top:443?allowInsecure=1#HK_AzadNet%2821%29
    trojan://ceaea123-1b4b-469b-8358-bcd5f5529305@usa.liangyuandian.top:443?allowInsecure=1#HK_AzadNet%2822%29
    trojan://b2119912-55bb-4e69-a002-b1d2ae75e47e@jp.iamnotagoodman.com:443?allowInsecure=1#HK_AzadNet%2823%29
    trojan://b42c2c42-b8ef-4cbe-8443-8870cf10875a@16.163.189.245:443?allowInsecure=1&sni=data-hk.efyunpan.com#HK_AzadNet%281%29
    trojan://18304160-03d4-4c55-95c1-586c0a5f3a0a@ap.liangyuandian.top:443?allowInsecure=1#HK_AzadNet%2825%29
    trojan://4f8c0e41-dbdb-40f1-99cb-2c2a0b909b52@lux.iamnotagoodman.com:443?allowInsecure=1#HK_AzadNet%2826%29
    trojan://b27c853c-714a-45a5-be55-6451595a1b69@download2hkt.windowsupdate.lol:443?allowInsecure=1#HK_AzadNet%2829%29
    trojan://d4e41ff772c7fd45@45.11.104.94:3389?allowInsecure=1#HK_AzadNet%2830%29
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgzMSkiLCJhZGQiOiI4LjIxMC4xNTMuMjQyIiwicG9ydCI6IjQ4NTc3IiwidHlwZSI6Im5vbmUiLCJpZCI6ImRkM2M1Y2U0LTY3NDEtNGNkYi1hNTRkLWJmNDM0NzU5NjllNSIsImFpZCI6IjAiLCJuZXQiOiJodHRwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgzMikiLCJhZGQiOiI4LjIxMC4yNTMuOTMiLCJwb3J0IjoiMzEwODMiLCJ0eXBlIjoibm9uZSIsImlkIjoiZDIwNzBiOTctNmQ3Yy00NGRjLTljN2MtODRhOWM4OTE4MTVlIiwiYWlkIjoiMCIsIm5ldCI6Imh0dHAiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9KOayueeuoeegtOino+i1hOa6kOWQmykgNDEiLCJhZGQiOiIxNDEuMTAxLjExNC4xMTEiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjJiMjE0MTIyLTE5MDYtNDI4YS1iYmI3LWEwMzljYmI3Y2Q1YyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvOUpaRkRUS0UiLCJob3N0IjoiZnIxLnRydW1wMjAyMy5vcmciLCJ0bHMiOiJ0bHMifQ==
    ss://YWVzLTI1Ni1nY206a0RXdlhZWm9UQmNHa0M0@38.91.102.30:8881#US_AzadNet%2868%29
    ss://YWVzLTI1Ni1nY206ZmFCQW9ENTRrODdVSkc3@142.202.48.7:2376#US_142
    ssr://MTA0LjE0OS4xMzkuMTg5OjEwMDAyOmF1dGhfY2hhaW5fYTphZXMtMjU2LWNmYjp0bHMxLjJfdGlja2V0X2F1dGg6Wkc5dVozUmhhWGRoYm1jdVkyOXQvP2dyb3VwPVUxTlNVSEp2ZG1sa1pYSSZyZW1hcmtzPVZWTmZNVEEwTGpFME9TNHhNemt1TVRnNVh6QXhNRGd5TURJek56ZGpOQzAwTkRWekpRJm9iZnNwYXJhbT0mcHJvdG9wYXJhbT0
    ss://YWVzLTI1Ni1nY206ZTRGQ1dyZ3BramkzUVk@169.197.141.14:9101#US_AzadNet%2833%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9KOayueeuoeegtOino+i1hOa6kOWQmykgMzEiLCJhZGQiOiIxNDEuMTkzLjIxMy4xMCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMjBlOTI4ODEtNWZiNC00YjA1LWJjNzctNTc5Mjk0NzZkYzY5IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9zaGlya2VyIiwiaG9zdCI6InNnLWdjb3JlLnNoYXJlY2VudHJlLm9ubGluZSIsInRscyI6InRscyJ9
    ssr://NDUuNjMuNDguNDoxMDAwMTphdXRoX2NoYWluX2E6YWVzLTI1Ni1jZmI6dGxzMS4yX3RpY2tldF9hdXRoOlpHOXVaM1JoYVhkaGJtY3VZMjl0Lz9ncm91cD1VMU5TVUhKdmRtbGtaWEkmcmVtYXJrcz1WVk5mTkRVdU5qTXVORGd1TkY4d01UQTNNakF5TXpFM01UVXRNVFkxYzNOeSZvYmZzcGFyYW09JnByb3RvcGFyYW09
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9KOayueeuoeegtOino+i1hOa6kOWQmykgMTEiLCJhZGQiOiIxNzIuNjcuMjIyLjQ2IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjZmZWExNjQ5LTQyNWItNDA5Mi1iZjUzLTI5NzkyMTUyYzkyNSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvc3Noa2l0L2ZkZmFkc2ZhLzYzODQ4YmZlMjI4ZmQvIiwiaG9zdCI6InVzLWxiLnNzaGtpdC5vcmciLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVNfQXphZE5ldCgxMDQpIiwiYWRkIjoiNTEuODEuMjIwLjE5NSIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI2ZmVhMTY0OS00MjViLTQwOTItYmY1My0yOTc5MjE1MmM5MjUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3NzaGtpdC83dWplanMvNjM3MmVhYzYxZDU0My8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71DbG91ZEZsYXJl5YWs5Y+4Q0RO6IqC54K5IDIzIiwiYWRkIjoicG93ZXJzZXJ2aWNlLmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMDc2NGE1OTgtODJjNC00YjQxLWJhMTAtNTUxYTYyNWJlZWQ1IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoidWsyLnYycmF5c2Vydi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggdjJyYXlmcmVlLmV1Lm9yZyAtIOe+juWbvUNsb3VkRmxhcmXlhazlj7hDRE7oioLngrkgMjMiLCJhZGQiOiJwb3dlcnNlcnZpY2UuY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIwNzY0YTU5OC04MmM0LTRiNDEtYmExMC01NTFhNjI1YmVlZDUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiJ1azIudjJyYXlzZXJ2LmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzAxMTIxNjYwIiwiYWRkIjoidWljZG4uY2YiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiNmZlYTE2NDktNDI1Yi00MDkyLWJmNTMtMjk3OTIxNTJjOTI1IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9zc2hraXQvZmRmYWRzZmEvNjM4NDhiZmUyMjhmZC8iLCJob3N0IjoidXMtbGIuc3Noa2l0Lm9yZyIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71DbG91ZEZsYXJl5YWs5Y+4Q0RO6IqC54K5IDMzIiwiYWRkIjoidjJyYXkub25saW5lIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIyRjA5NDg0NS1FMkJELUVCRjctREVCNy05OTU5OTI0MzZGQUYiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3NwZWVkdGVzdCIsImhvc3QiOiJWaWVubmEudjJyYXkub25saW5lIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9KOayueeuoeegtOino+i1hOa6kOWQmykgMyIsImFkZCI6ImhrODAtMi5zYW5mZW4wMDEucGljcyIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI1MDZkOTNlYy1mZmRiLTQxY2QtYmJjMy0zNjcwMzljNGIxOGYiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3poLWNuLyIsImhvc3QiOiJ3d3cuYmFpZHUuY29tIiwidGxzIjoiIn0=
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@72.140.224.195:810#CA_AzadNet%2822%29
    vmess://eyJ2IjoiMiIsInBzIjoiQ0FfQXphZE5ldCgyKSIsImFkZCI6IjM1LjE4My4xMjguODMiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjEyZTA4MjU2LWRhNWQtNGIxYy1hZWNhLThjOTczY2NjZWVmOCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvRmFsbGluZzQyYXdzeXBjYW5vZGUiLCJob3N0IjoiIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiQ0FfQXphZE5ldCgxKSIsImFkZCI6IjE1OS44OS4xMjAuNjMiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImYzOGZjMTcwLTkwNGUtNDg1My1jM2JiLWM3MGM4YjgyOGZlNiIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL0ZhbGxpbmc0MmF3c3lwY2Fub2RlIiwiaG9zdCI6IiIsInRscyI6InRscyJ9
    trojan://838c5357-cb93-48ff-a1cc-acea4491b3e7@149.56.132.41:443?allowInsecure=1&sni=ca1.trojanvh.xyz#CA_AzadNet
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm73mg6Dmma5IUCA0IiwiYWRkIjoiMTUuMjA0LjMxLjYzIiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjZkMWYwZWNhLWY1MDgtNGRhNC05YWJhLTAzNzhmODVmODNkMCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71DbG91ZEZsYXJl6IqC54K5IDMiLCJhZGQiOiJnZXQudGVjaCIsInBvcnQiOiIyMDg2IiwidHlwZSI6Im5vbmUiLCJpZCI6IjQ1OGNhYWVkLWM3YTctNDZhZS1iYzM3LTkwNzI0ZDQwZGMzMyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6InNmb2RvLmNsb3VkZmxhcmUucXVlc3QiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm73mg6Dmma5IUCAxIiwiYWRkIjoiaGs4MC5zYW5mZW4wMDEucGljcyIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI1MDZkOTNlYy1mZmRiLTQxY2QtYmJjMy0zNjcwMzljNGIxOGYiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiJ3d3cuYmFpZHUuY29tIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiVVNfQXphZE5ldCIsImFkZCI6IjE2Mi4xNTkuMTM3LjIxNSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNWNlOWNiMGQtNmIxMi00ZGJkLTkxMTQtNzRmZDExZGM2ZjM1IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiVVNfQXphZE5ldCgxKSIsImFkZCI6IjE5OC40MS4yMjMuODciLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjIwZTkyODgxLTVmYjQtNGIwNS1iYzc3LTU3OTI5NDc2ZGM2OSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvc2hpcmtlciIsImhvc3QiOiIiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrvCfh7MgZ2l0aHViLmNvbS9mcmVlZnEgLSDljbDluqYgIDQwIiwiYWRkIjoiNjguMTgzLjgzLjk0IiwicG9ydCI6IjU5NDc3IiwidHlwZSI6Im5vbmUiLCJpZCI6ImI4ZjZhNzFjLTY5MjUtNGU4NC1mYjkzLTZlNTRmOGQ5OGIyNSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Ht/Cfh7og5L+E572X5pav6IGU6YKmXzAxMTIwMDciLCJhZGQiOiIxODUuMjIuMTUzLjE2IiwicG9ydCI6IjMxOTkwIiwidHlwZSI6Im5vbmUiLCJpZCI6ImE2YTM3ZTA0LTVlODEtNDRjOS1iZTUzLWJhYTNmZjQ2ZWI4YiIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqvCfh7og5qyn5rSyKOayueeuoeegtOino+i1hOa6kOWQmykgMjIiLCJhZGQiOiIxOTAuOTMuMjQ2LjMiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjU2YTIxODhiLTJhYjctNDAyYy1iOWI4LTM0ODQ3ZmRmMDk1OCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvNVFOUk9TUlYiLCJob3N0Ijoib3BsZzEuemh1amljbjIuY29tIiwidGxzIjoidGxzIn0=
    trojan://cf4295378e209e70d12c5bdd017144dfd1c772d3@43.153.30.20:8443?allowInsecure=1#mianfeifq_010720231715-82trojan
    trojan://cf4295378e209e70d12c5bdd017144dfd1c772d3@43.154.228.196:8443?allowInsecure=1#mianfeifq_010320232330-3trojan
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@93.186.201.124:810#DE_AzadNet
    vmess://eyJ2IjoiMiIsInBzIjoiX1VBX+asoui/juiuoumYhXl1aeenkeaKgCIsImFkZCI6IjUuMzQuMTgyLjEyIiwicG9ydCI6IjEwMDAwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjVmNWExMmEwLThkZGEtMTFlZC04M2UxLTQzNTBjOTJmZmZlOCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvdnBuamFudGl0IiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Ht/Cfh7og5L+E572X5pavKOayueeuoeegtOino+i1hOa6kOWQmykgMiIsImFkZCI6IjIzLjIyNy4zOC4xMDAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjdiMWIyZmEzLWUzNjEtNDhjYy1iNzNkLTJjOTYzNmM3NmY0YiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvVU1XMzYyNjIiLCJob3N0IjoidjJyYXkxLnpodWppY24yLm9yZyIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Ht/Cfh7og5L+E572X5pavKOayueeuoeegtOino+i1hOa6kOWQmykiLCJhZGQiOiIxNjIuMTU5LjEyOC43IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxOTkyNGJlNy1kYjFjLTRiMzItOGRiYy1hZWM2OGUwYmJmM2UiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiJwbDEudjJyYXlzZXJ2LmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrvCfh7kg5oSP5aSn5YipIiwiYWRkIjoiMjEzLjEwOS4xOTIuOTgiLCJwb3J0IjoiNjAwMDAiLCJ0eXBlIjoibm9uZSIsImlkIjoiMWJmMmNiNzAtOWZkZS00YjYwLThkZjctMjllOTMyZmRmNzYzIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6InBsMS52MnJheXNlcnYuY29tIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi5pyq55+lXzAxMTIyMjUiLCJhZGQiOiIxOTguNDEuMjA1LjE4MSIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI2ZmVhMTY0OS00MjViLTQwOTItYmY1My0yOTc5MjE1MmM5MjUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3NzaGtpdC9mZGZhZHNmYS82Mzg0OGJmZTIyOGZkLyIsImhvc3QiOiJ1cy1sYi5zc2hraXQub3JnIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hu/Cfh7Mg6LaK5Y2XXzAxMTIxMjciLCJhZGQiOiIxMDMuMTY2LjE4My4yMjYiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiZWY5MTljNjctNjYzOC00NDE2LTkxYWYtOWExM2ZmZTViOWNhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii90YW5kdW5nMjg4LmNsaWNrIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hq/Cfh7cg5rOV5Zu9XzAxMTIxMzMiLCJhZGQiOiIxNzMuMjQ1LjQ5LjExMSIsInBvcnQiOiI4NDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImE2YTM3ZTA0LTVlODEtNDRjOS1iZTUzLWJhYTNmZjQ2ZWI4YiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvOGNkYTQ4YjMiLCJob3N0IjoidXMtMTcxLTc4LnNob3B0dW5uZWwubGl2ZSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqvCfh7og5qyn5rSyKOayueeuoeegtOino+i1hOa6kOWQmykgMzIiLCJhZGQiOiI0NS4xMzYuMjQ0LjE4MSIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiJhMjU4ODFmMy05NjdmLTMyNjUtYmM3Zi05ZTY2ODU3YjAxNmIiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2ZyLXVubGltaXR4eHgiLCJob3N0IjoiNDUuMTM2LjI0NC4xODEiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiRklfQXphZE5ldCIsImFkZCI6IjEzNS4xODEuMjM1LjIxIiwicG9ydCI6IjI1MDM0IiwidHlwZSI6Im5vbmUiLCJpZCI6ImU1NDlmYzhkLTI0MTYtNDZmNy1hYWRjLTg3NDc1NTMwOTFiOSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqvCfh7og5qyn5rSyKOayueeuoeegtOino+i1hOa6kOWQmykgMiIsImFkZCI6IjUxLjc3LjIxMi4xNDUiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiNWY2ZTQyYmItMmZkMS00NzhiLThmMGYtZTUyYjJkNmY3NjUyIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii92bWVzcyIsImhvc3QiOiI1MS43Ny4yMTIuMTQ1IiwidGxzIjoiIn0=
    trojan://a2c8194b-fcfd-4c39-a6bd-31ea9f4ea671@5.135.235.160:443?allowInsecure=1&sni=upload.soft98.download#FR_AzadNet%2815%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqvCfh7og5qyn5rSyKOayueeuoeegtOino+i1hOa6kOWQmykgOSIsImFkZCI6IjUxLjY4LjEzOS4yMiIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiJjNjc0NGM0NC00ZWI3LTQ4ZDUtYTg3OS1hMTA0NzRlMmJhMzQiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3ZtZXNzIiwiaG9zdCI6IjUxLjY4LjEzOS4yMiIsInRscyI6IiJ9
    trojan://211f5876-8c89-4d97-9004-ff16acddd506@uk1.trojanvh.xyz:80?allowInsecure=1#%F0%9F%87%AA%F0%9F%87%BA%20%E6%AC%A7%E6%B4%B2%28%E6%B2%B9%E7%AE%A1%E7%A0%B4%E8%A7%A3%E8%B5%84%E6%BA%90%E5%90%9B%29%203
    vmess://eyJ2IjoiMiIsInBzIjoi5Lqa5rSyKOayueeuoeegtOino+i1hOa6kOWQmykgNCIsImFkZCI6IjIyMy4xMTIuMjI3LjI0IiwicG9ydCI6IjUwMDEyIiwidHlwZSI6Im5vbmUiLCJpZCI6IjFiZjJjYjcwLTlmZGUtNGI2MC04ZGY3LTI5ZTkzMmZkZjc2MyIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    trojan://54080134-2cba-4535-8599-95650bd9aa54@152.67.160.174:443?allowInsecure=1#IN_AzadNet%281%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Ht/Cfh7og5L+E572X5pavKOayueeuoeegtOino+i1hOa6kOWQmykgNyIsImFkZCI6Ijg1LjIzOS42My4xMTkiLCJwb3J0IjoiNjAwMDAiLCJ0eXBlIjoibm9uZSIsImlkIjoiMWJmMmNiNzAtOWZkZS00YjYwLThkZjctMjllOTMyZmRmNzYzIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    trojan://b3902e81-6260-4932-bcc9-708445fe40b4@frt2.sshocean.net:443?allowInsecure=1#mianfeifq_01112023fc1f-606trojan
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Ht/Cfh7og5L+E572X5pavKOayueeuoeegtOino+i1hOa6kOWQmykgNSIsImFkZCI6ImNmLWx0LnNoYXJlY2VudHJlLm9ubGluZSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMjBlOTI4ODEtNWZiNC00YjA1LWJjNzctNTc5Mjk0NzZkYzY5IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9zaGlya2VyIiwiaG9zdCI6InVzLWRwLnNoYXJlY2VudHJlLm9ubGluZSIsInRscyI6InRscyJ9
    

</details>

### 所有节点
合并节点总数: `3133`
[节点链接](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [pojiezhiyuanjun/freev2](https://github.com/pojiezhiyuanjun/freev2), 节点数量: `96`
- [Alvin9999/pac2](https://github.com/Alvin9999/pac2), 节点数量: `82`
- [xiyaowong/freeFQ](https://github.com/xiyaowong/freeFQ), 节点数量: `141`
- [freefq/free](https://github.com/freefq/free), 节点数量: `53`
- [learnhard-cn/free_proxy_ss](https://github.com/learnhard-cn/free_proxy_ss), 节点数量: `9`
- [vpei/Free-Node-Merge](https://github.com/vpei/Free-Node-Merge), 节点数量: `1`
- [colatiger/v2ray-nodes](https://github.com/colatiger/v2ray-nodes), 节点数量: `1`
- [AzadNetCH/Clash](https://github.com/AzadNetCH/Clash), 节点数量: `3723`
- [ssrsub/ssr](https://github.com/ssrsub/ssr), 节点数量: `241`
- [Leon406/SubCrawler](https://github.com/Leon406/SubCrawler), 节点数量: `8581`
- [yu-steven/openit](https://github.com/yu-steven/openit), 节点数量: `1`
- [Jsnzkpg/Jsnzkpg](https://github.com/Jsnzkpg/Jsnzkpg), 节点数量: `42`
- [ermaozi/get_subscribe](https://github.com/ermaozi/get_subscribe), 节点数量: `43`
- [gfwglass 节点池](https://gfwglass.tk), 节点数量: `1`
- [Meteor-1337/Meteor](https://github.com/Meteor-1337/Meteor), 节点数量: `1`
- [ronghuaxueleng/get_v2](https://github.com/ronghuaxueleng/get_v2), 节点数量: `49`
- [anaer/Sub](https://github.com/anaer/Sub), 节点数量: `147`
- [xrayfree/free-ssr-ss-v2ray-vpn-clash](https://github.com/xrayfree/free-ssr-ss-v2ray-vpn-clash), 节点数量: `63`
- [aiboboxx/v2rayfree](https://github.com/aiboboxx/v2rayfree), 节点数量: `46`
- [Pawdroid/Free-servers](https://github.com/Pawdroid/Free-servers), 节点数量: `5`
- [kxswa/k](https://github.com/kxswa/k), 节点数量: `83`
- [Nodefree.org](https://github.com/Fukki-Z/nodefree), 节点数量: `50`
- [Rokate/Proxy-Sub](https://github.com/Rokate/Proxy-Sub), 节点数量: `394`
- [mianfeifq/share](https://github.com/mianfeifq/share), 节点数量: `244`
- [peasoft/NoMoreWalls](https://github.com/peasoft/NoMoreWalls), 节点数量: `316`
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
