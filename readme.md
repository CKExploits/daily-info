# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210331 | Tavis 开源了一个测试 setuid 程序在资源受限环境运行行为的小工具 | https://github.com/taviso/scanlimits| 
| 20210331 | 微软发布的《Security baseline for Office 365 ProPlus》 | https://techcommunity.microsoft.com/t5/microsoft-security-baselines/security-baseline-for-office-365-proplus-v2103-march-2021-draft/ba-p/2228388| 
| 20210331 | Windows TPM 驱动（tpm.sys）信息泄露漏洞 PoC（CVE-2021-1656） | https://github.com/waleedassar/CVE-2021-1656| 
| 20210331 | Fuzzing 方向的 Paper 收集，按照细分的领域整理 | https://wcventure.github.io/FuzzingPaper/| 
| 20210331 | kCTF - Google 开源了一套基于 Kubernetes 的 CTF 基础设施搭建框架 | https://google.github.io/kctf/| 
| 20210331 | Fuzzing sockets: Apache HTTP, Part 2: Custom Interceptors | https://securitylab.github.com/research/fuzzing-apache-2/| 
| 20210331 | 利用 Wind Vision App 认证过程以及 IPC 通信过程的漏洞实现免费看数字电视 | https://labs.f-secure.com/blog/wind-vision-writeup/| 
| 20210331 | 卡巴斯基发了一篇针对 APT 10 组织近期 A41APT 攻击行动的分析报告 | https://securelist.com/apt10-sophisticated-multi-layered-loader-ecipekac-discovered-in-a41apt-campaign/101519/| 
| 20210331 | FluBot：一场席卷欧洲的移动银行木马攻击活动 | https://blogs.360.cn/post/analysis-of-FluBot.html| 
| 20210331 | FuzzOS：编写ACPI SPCR解析器+串行驱动程序视频。 | https://www.youtube.com/watch?v=Pw1SiVF7wjU&feature=youtu.be| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210331 | 驱动病毒那些事(一)----基础 | https://www.sec-in.com/article/989| 
| 20210331 | 国际视野看工控靶场的融合与创新 | https://mp.weixin.qq.com/s/PToOOhcCKe6bjQvrdYBXYg| 
| 20210331 | 符号执行Symcc与模糊测试AFL结合实践 | https://mp.weixin.qq.com/s/_qj40FMl7UwDswJ89z5uiA| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210331T23:35:24Z | CVE-2021-1699 | POC for CVE-2021-1699 | https://github.com/waleedassar/CVE-2021-1699 | Windows (modem.sys) Information Disclosure Vulnerability| 
| 20210331T21:44:59Z | cve-2021-3449 | CVE-2021-3449 OpenSSL denial-of-service exploit 👨🏻‍💻 | https://github.com/terorie/cve-2021-3449 | An OpenSSL TLS server may crash if sent a maliciously crafted renegotiation ClientHello message from a client. If a TLSv1.2 renegotiation ClientHello omits the signature_algorithms extension (where it was present in the initial ClientHello), but includes a signature_algorithms_cert extension then a NULL pointer dereference will result, leading to a crash and a denial of service attack. A server is only vulnerable if it has TLSv1.2 and renegotiation enabled (which is the default configuration). OpenSSL TLS clients are not impacted by this issue. All OpenSSL 1.1.1 versions are affected by this issue. Users of these versions should upgrade to OpenSSL 1.1.1k. OpenSSL 1.0.2 is not impacted by this issue. Fixed in OpenSSL 1.1.1k (Affected 1.1.1-1.1.1j).| 
| 20210331T20:49:38Z | CVE-2020-13401 | Study on CVE-2020-13401 vulnerability of containers in dockers older than 19.03.11 | https://github.com/mmzaeimi/Docker-Container-CVE-2020-13401 | An issue was discovered in Docker Engine before 19.03.11. An attacker in a container, with the CAP_NET_RAW capability, can craft IPv6 router advertisements, and consequently spoof external IPv6 hosts, obtain sensitive information, or cause a denial of service.| 
| 20210331T19:36:29Z | CVE-2021-29349 | Null | https://github.com/0xBaz/CVE-2021-29349 | Mahara 20.10 is affected by Cross Site Request Forgery (CSRF) that allows a remote attacker to remove inbox-mail on the server. The application fails to validate the CSRF token for a POST request. An attacker can craft a module/multirecipientnotification/inbox.php pieform_delete_all_notifications request, which leads to removing all messages from a mailbox.| 
| 20210331T17:12:35Z | CVE-2021-1656 | Null | https://github.com/waleedassar/CVE-2021-1656 | TPM Device Driver Information Disclosure Vulnerability| 
| 20210331T15:50:29Z | CVE-2021-21975 | CVE-2021-21975 vRealize Operations Manager SSRF | https://github.com/Al1ex/CVE-2021-21975 | Server Side Request Forgery in vRealize Operations Manager API (CVE-2021-21975) prior to 8.4 may allow a malicious actor with network access to the vRealize Operations Manager API can perform a Server Side Request Forgery attack to steal administrative credentials.| 
| 20210331T14:42:21Z | CVE-2020-17136 | CVE-2020-17136 exploit | https://github.com/xyddnljydd/CVE-2020-17136 | Windows Cloud Files Mini Filter Driver Elevation of Privilege Vulnerability This CVE ID is unique from CVE-2020-17103, CVE-2020-17134.| 
| 20210331T13:58:18Z | 未知编号 | Null | https://github.com/feihong-cs/Attacking_Shiro_with_CVE_2020_2555 | 未查询到CVE信息| 
| 20210331T06:44:09Z | CVE-2021-3156 | Sudo Baron Samedit Exploit | https://github.com/worawit/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210331T03:49:34Z | CVE-2021-26828 | Null | https://github.com/hevox/CVE-2021-26828_ScadaBR_RCE | 未查询到CVE信息| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210331T22:40:35Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 375 | 10| 
| 20210331T21:45:44Z | Repo for KLEE soils project: incubation/respiration data, soil C/N data, associated analyses | https://github.com/elizabethforbes/KLEEsoils_project | 0 | 0| 
| 20210331T20:14:18Z | A personnal UI library made as an excuse to have a published UI package | https://github.com/Liinkiing/klee | 5 | 1| 
| 20210331T16:12:08Z | Config files for my GitHub profile. | https://github.com/kleepout/kleepout | 0 | 0| 
| 20210331T14:12:19Z | Create CFGs and compute complexity metrics for Python, C++, and Java code. | https://github.com/hmc-alpaqa/metrinome | 7 | 0| 
| 20210331T09:04:48Z | KLEE in the browser | https://github.com/klee/klee-web | 44 | 12| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210331T10:48:32Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 114 | 25| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210331T23:42:39Z | A Kindle jailbreak by Kaneki07 | https://github.com/Kaneki07/SphinxKJB | 0 | 0| 
| 20210331T23:30:17Z | PS4 Exploit Host | https://github.com/Night-King-Host/Night-King-Host.github.io | 6 | 3| 
| 20210331T23:28:46Z | A Remote Code Execution (RCE) exploit for Huawei HG532d based on CVE-2017-17215 vulnerability. Modded from original PoC code from exploit-db.com | https://github.com/wilfred-wulbou/HG532d-RCE-Exploit | 0 | 1| 
| 20210331T23:10:08Z | Exploit Development and Reverse Engineering with GDB Made Easy | https://github.com/pwndbg/pwndbg | 3547 | 518| 
| 20210331T22:51:08Z | Null | https://github.com/caddickzac/Motivated-Reasoning-in-an-Explore-Exploit-Task | 0 | 0| 
| 20210331T22:45:33Z | This bash script will help you to hack remote hosts  | https://github.com/FabioDefilippo/linuxallremote | 10 | 1| 
| 20210331T22:33:20Z | Null | https://github.com/Kayky-cmd/CORS-Exploit | 0 | 0| 
| 20210331T22:32:39Z | Exploit para vulnerabiliade de Content-Security-Politic | https://github.com/Kayky-cmd/Exploit-CORS | 0 | 0| 
| 20210331T22:24:10Z | Common exploitaton tecniques | https://github.com/sal65535/ExploitationCompassSheet | 1 | 0| 
| 20210331T21:50:56Z | Blog personal dedicado al exploiting, reversing y CTFs | https://github.com/Pwn2Ninj4/pwn2ninj4.github.io | 0 | 1| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210331T21:06:31Z | AMWScan (PHP Antimalware Scanner) is a free tool to scan php files and analyze your project to find any malicious code inside it. | https://github.com/marcocesarato/PHP-Antimalware-Scanner | 187 | 34| 
| 20210331T20:41:03Z | Null | https://github.com/cranelab/history-of-backdoors | 0 | 0| 
| 20210331T20:39:51Z | Minecraft Server Backdoor Plugin | https://github.com/NeunXKILLER20/PluginPwn | 1 | 0| 
| 20210331T19:53:08Z | Null | https://github.com/EjHvorSerDuVildUdJim/backdoor | 0 | 0| 
| 20210331T18:51:50Z | Null | https://github.com/Delle9999/backdoor | 0 | 0| 
| 20210331T12:19:44Z | https://github.blog/2021-03-16-using-github-code-scanning-and-codeql-to-detect-traces-of-solorigate-and-other-backdoors/ | https://github.com/434791829/License-number-12 | 1 | 0| 
| 20210331T09:24:21Z | Null | https://github.com/xpf/Backdoor-Learning-arXiv | 0 | 0| 
| 20210331T03:26:55Z | Python 3 Reverse Shell | https://github.com/trackmastersteve/shell | 12 | 4| 
| 20210331T03:07:51Z | Invisible, customizable backdoor for Minecraft Spigot Plugins. | https://github.com/ThiccIndustries/Minecraft-Backdoor | 2 | 1| 
| 20210331T01:28:34Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 200 | 34| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210331T12:34:57Z | Null | https://github.com/fuzzsa/fuzzsa-bugs | 0 | 1| 
| 20210331T12:30:33Z | AFLNet: A Greybox Fuzzer for Network Protocols (https://thuanpv.github.io/publications/AFLNet_ICST20.pdf) | https://github.com/aflnet/aflnet | 386 | 63| 
| 20210331T12:13:31Z | Null | https://github.com/primait/ex_fuzzywuzzy | 0 | 0| 
| 20210331T12:09:04Z | 📨 Responsive email template generator. | https://github.com/luangjokaj/fuzzymail | 114 | 4| 
| 20210331T12:03:01Z | Null | https://github.com/kinzhong/fuzzing-automation-tools | 0 | 0| 
| 20210331T11:43:22Z | Null | https://github.com/FDU-Program-Analysis/chunk-fuzzer-pass | 0 | 0| 
| 20210331T11:09:42Z | Null | https://github.com/Yin-Lynn-Htun/Fuzzy-shop | 0 | 0| 
| 20210331T11:07:24Z | Null | https://github.com/s9varesc/url-fuzzing | 1 | 1| 
| 20210331T10:51:22Z | Null | https://github.com/s9varesc/url-fuzzing-docker | 0 | 0| 
| 20210331T10:35:48Z | Hacking tools written by me. IP fortune, webmap -- web vulns scanner, rtsp brute+fuzz, and more. | https://github.com/fagcinsk/h4ck | 1 | 0| 



# 日更新程序
