# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210217 | 做信息安全BP的一些感悟 | https://mp.weixin.qq.com/s/qygwMIGX3PhbnKuPwQqfUQ| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210217T12:03:28Z | CVE-2021-1727 | Null | https://github.com/klinix5/CVE-2021-1727 | 未查询到CVE信息| 
| 20210217T11:43:43Z | CVE-2021-24085 | Null | https://github.com/sourceincite/CVE-2021-24085 | 未查询到CVE信息| 
| 20210217T10:59:58Z | CVE-2021-26700 | RCE in NPM VSCode Extention | https://github.com/jackadamson/CVE-2021-26700 | 未查询到CVE信息| 
| 20210217T09:23:59Z | CVE-2020-7247 | OpenSMTPD 6.4.0 - 6.6.1 Remote Code Execution PoC exploit | https://github.com/QTranspose/CVE-2020-7247-exploit | smtp_mailaddr in smtp_session.c in OpenSMTPD 6.6, as used in OpenBSD 6.6 and other products, allows remote attackers to execute arbitrary commands as root via a crafted SMTP session, as demonstrated by shell metacharacters in a MAIL FROM field. This affects the %uncommented% default configuration. The issue exists because of an incorrect return value upon failure of input validation.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210217T11:43:31Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 57 | 3| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210217T05:59:09Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 97 | 22| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210217T02:15:20Z | A phased, evasive Path Traversal + LFI scanning & exploitation tool in Python | https://github.com/VainlyStrain/Vailyn | 95 | 4| 
| 20210217T02:02:45Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 9 | 4| 
| 20210217T01:46:58Z | GhostPing Exploit no patched | https://github.com/Monst3red/GhostPing-Exploit | 0 | 1| 
| 20210217T01:44:36Z | Zerologon Check and Exploit - Discovered by Tom Tervoort of Secura and expanded on @Dirkjanm%s cve-2020-1472 coded example | https://github.com/sho-luv/zerologon | 1 | 0| 
| 20210217T01:39:41Z | Windows exploitation and customization tool. Under development. | https://github.com/coredoescode/c0deblack | 0 | 0| 
| 20210217T01:23:39Z | Essa exploit localiza um número, retorna operadora é estado. | https://github.com/igorsouza60/locazila_numero | 0 | 0| 
| 20210217T01:10:34Z | local aux = {}  local getGc = getgc local getInfo = debug.getinfo or getinfo local getUpvalue = debug.getupvalue or getupvalue or getupval local getConstants = debug.getconstants or getconstants or getconsts local isXClosure = is_synapse_function or issentinelclosure or is_protosmasher_closure or is_sirhurt_closure or checkclosure local isLClosure = islclosure or is_l_closure or (iscclosure and function(f) return not iscclosure(f) end)  assert(getGc and getInfo and getConstants and isXClosure, %Your exploit is not supported%)  local function matchConstants(closure, list)     if not list then         return true     end          local constants = getConstants(closure)          for index in pairs(list) do         if not constants[index] then             return false         end     end          return true end  local function searchClosure(script, name, upvalueIndex, constants)     for _i, v in pairs(getGc()) do         local parentScript = rawget(getfenv(v), %script%)          if type(v) == %function% and              isLClosure(v) and              not isXClosure(v) and              (                 (script == nil and parentScript.Parent == nil) or script == parentScript             )              and pcall(getUpvalue, v, upvalueIndex)         then             if ((name and name ~= %Unnamed function%) and getInfo(v).name == name) and matchConstants(v, constants) then                 return v             elseif (not name or name == %Unnamed function%) and matchConstants(v, constants) then                 return v             end         end     end end  aux.searchClosure = searchClosure  return aux | https://github.com/corpes45/kik | 0 | 0| 
| 20210217T01:00:32Z | Various ASM, C and C++ tools, shellcodes and exploit experiments. | https://github.com/forrest-orr/ExploitDev | 51 | 5| 
| 20210217T00:57:38Z | Null | https://github.com/nobelherrrera/wx-exploit-suggester-py2 | 0 | 0| 
| 20210217T00:56:56Z | Null | https://github.com/nobelherrrera/win-exploit-suggester-py-2 | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210217T02:56:54Z | An AWS Pentesting tool that lets you use one-liner commands to backdoor an AWS account%s resources with a rogue AWS account - or share the resources with the entire internet 😈 | https://github.com/hirajanwin/endgame | 29 | 170| 
| 20210217T02:49:10Z | An AWS Pentesting tool that lets you use one-liner commands to backdoor an AWS account%s resources with a rogue AWS account - or share the resources with the entire internet 😈 | https://github.com/jeffmcjunkin/endgame | 3 | 1| 
| 20210217T01:21:36Z | Null | https://github.com/arquinity/PHP_Backdoor | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 



# 日更新程序
