port: 7890
socks-port: 7891
allow-lan: true
mode: Rule
log-level: info
external-controller: 127.0.0.1:9090
proxies:
  - {name: 🇭🇰 香港01, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: hk-gcore.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: hk-gcore.sharecentre.online}}}
  - {name: 🇭🇰 香港02, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: gcore-hk.cloudflare.quest}}}
  - {name: 🇸🇬 狮城01, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: sg-gcore.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: sg-gcore.sharecentre.online}}}
  - {name: 🇸🇬 狮城03, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: gcore-sg.cloudflare.quest}}}
  - {name: 🇯🇵 日本01, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: jp1.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: jp1.sharecentre.online}}}
  - {name: 🇯🇵 日本02, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: gcore-jp.cloudflare.quest}}}
  - {name: 🇩🇪 德国01, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: de-1.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: de-1.sharecentre.online}}}
  - {name: 🇩🇪 德国02, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: de-2.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: de-2.sharecentre.online}}}
  - {name: 🇬🇧 英国01, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: uk-1.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: uk-1.sharecentre.online}}}
  - {name: 🇬🇧 英国02, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: uk-2.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: uk-2.sharecentre.online}}}
  - {name: 🇸🇬 狮城02, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: sg-1.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: sg-1.sharecentre.online}}}
  - {name: 🇺🇲 美国01, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: us-dp2.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: us-dp2.sharecentre.online}}}
  - {name: 🇺🇲 美国02, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: gcore-us.cloudflare.quest}}}
  - {name: "柬埔寨01[Netflix]", server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: kh.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: kh.sharecentre.online}}}
  - {name: "🇹🇷 土耳其01[Netflix]", server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: GCORE-TR.cloudflare.quest}}}
  - {name: 🇻🇳 越南01, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: vn.cloudflare.quest}}}
  - {name: 🇮🇳 印度01, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: gcore-in.cloudflare.quest}}}
  - {name: 波兰01, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: waw.cloudflare.quest}}}
  - {name: 🇫🇷 法国01, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: france.cloudflare.quest}}}
  - {name: 🇫🇷 法国02, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: fr.cloudflare.quest}}}
  - {name: 🇳🇱 荷兰01, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: netherlands.cloudflare.quest}}}
  - {name: 🇳🇱 荷兰02, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: scw.cloudflare.quest}}}
  - {name: 🇨🇦 加拿大01, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: ca-help.cloudflare.quest}}}
  - {name: "爱沙尼亚[Netflix]", server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: ee.cloudflare.quest}}}
  - {name: 佬P公益项目, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: de-1.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: de-1.sharecentre.online}}}
  - {name: 佬P客栈, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: de-1.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: de-1.sharecentre.online}}}
  - {name: 晚高峰秒4K, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: de-1.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: de-1.sharecentre.online}}}
  - {name: 以下节点为中转Test, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: de-1.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: de-1.sharecentre.online}}}
  - {name: 不保证活久, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: de-1.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: de-1.sharecentre.online}}}
  - {name: 🇪🇸 日本TEST, server: 20.210.192.230, port: 27692, type: vmess, uuid: 95bcf8c2-4b62-403f-afb3-bdbf171ddfcd, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false}
  - {name: 🇪🇸 香港TEST, server: 20.205.5.230, port: 26082, type: vmess, uuid: 41244752-c7d0-408d-d947-d9da6b501649, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false}
proxy-groups:
  - name: 🚀 节点选择
    type: select
    proxies:
      - ♻️ 自动选择
      - 🇭🇰 香港节点
      - 🇨🇳 台湾节点
      - 🇸🇬 狮城节点
      - 🇯🇵 日本节点
      - 🇺🇲 美国节点
      - 🌀 手动切换
      - 🎯 全球直连
  - name: 🌀 手动切换
    type: select
    proxies:
      - 🇭🇰 香港01
      - 🇭🇰 香港02
      - 🇸🇬 狮城01
      - 🇸🇬 狮城03
      - 🇯🇵 日本01
      - 🇯🇵 日本02
      - 🇩🇪 德国01
      - 🇩🇪 德国02
      - 🇬🇧 英国01
      - 🇬🇧 英国02
      - 🇸🇬 狮城02
      - 🇺🇲 美国01
      - 🇺🇲 美国02
      - 柬埔寨01[Netflix]
      - 🇹🇷 土耳其01[Netflix]
      - 🇻🇳 越南01
      - 🇮🇳 印度01
      - 波兰01
      - 🇫🇷 法国01
      - 🇫🇷 法国02
      - 🇳🇱 荷兰01
      - 🇳🇱 荷兰02
      - 🇨🇦 加拿大01
      - 爱沙尼亚[Netflix]
      - 佬P公益项目
      - 佬P客栈
      - 晚高峰秒4K
      - 以下节点为中转Test
      - 不保证活久
      - 🇪🇸 日本TEST
      - 🇪🇸 香港TEST
  - name: ♻️ 自动选择
    type: url-test
    url: http://www.gstatic.com/generate_204
    interval: 300
    proxies:
      - 🇭🇰 香港节点
      - 🇨🇳 台湾节点
      - 🇸🇬 狮城节点
      - 🇯🇵 日本节点
      - 🇺🇲 美国节点
  - name: 🎶 网易音乐
    type: select
    proxies:
      - 🎯 全球直连
  - name: 📹 油管视频
    type: select
    proxies:
      - 🚀 节点选择
      - 🇸🇬 狮城节点
      - 🇭🇰 香港节点
      - 🇨🇳 台湾节点
      - 🇯🇵 日本节点
      - 🇺🇲 美国节点
      - 🌀 手动切换
      - 🎯 全球直连
  - name: 🎥 奈飞视频
    type: select
    proxies:
      - 🎥 奈飞节点
      - 🚀 节点选择
      - 🇸🇬 狮城节点
      - 🇭🇰 香港节点
      - 🇨🇳 台湾节点
      - 🇯🇵 日本节点
      - 🇺🇲 美国节点
      - 🌀 手动切换
      - 🎯 全球直连
  - name: 🎥 奈飞节点
    type: select
    proxies:
      - DIRECT
  - name: 📺 巴哈姆特
    type: select
    proxies:
      - 🇨🇳 台湾节点
      - 🚀 节点选择
      - 🌀 手动切换
      - 🎯 全球直连
  - name: 📺 哔哩哔哩
    type: select
    proxies:
      - 🎯 全球直连
      - 🇨🇳 台湾节点
      - 🇭🇰 香港节点
  - name: 🌍 国外媒体
    type: select
    proxies:
      - 🚀 节点选择
      - 🇭🇰 香港节点
      - 🇨🇳 台湾节点
      - 🇸🇬 狮城节点
      - 🇯🇵 日本节点
      - 🇺🇲 美国节点
      - 🌀 手动切换
      - 🎯 全球直连
  - name: 🌏 国内媒体
    type: select
    proxies:
      - 🎯 全球直连
      - 🚀 节点选择
      - 🌀 手动切换
  - name: 📲 电报消息
    type: select
    proxies:
      - 🚀 节点选择
      - 🇸🇬 狮城节点
      - 🇭🇰 香港节点
      - 🇨🇳 台湾节点
      - 🇯🇵 日本节点
      - 🇺🇲 美国节点
      - 🌀 手动切换
      - 🎯 全球直连
  - name: 📱 推特内容
    type: select
    proxies:
      - 🚀 节点选择
      - 🇸🇬 狮城节点
      - 🇭🇰 香港节点
      - 🇨🇳 台湾节点
      - 🇯🇵 日本节点
      - 🇺🇲 美国节点
      - 🌀 手动切换
      - 🎯 全球直连
  - name: 📢 谷歌FCM
    type: select
    proxies:
      - 🎯 全球直连
      - 🚀 节点选择
      - 🇺🇲 美国节点
      - 🇭🇰 香港节点
      - 🌀 手动切换
  - name: Ⓜ️ 微软云盘
    type: select
    proxies:
      - 🎯 全球直连
      - 🚀 节点选择
      - 🇺🇲 美国节点
      - 🇭🇰 香港节点
      - 🌀 手动切换
  - name: 🍎 苹果服务
    type: select
    proxies:
      - 🎯 全球直连
      - 🚀 节点选择
      - 🇺🇲 美国节点
      - 🇭🇰 香港节点
      - 🌀 手动切换
  - name: 🎮 游戏平台
    type: select
    proxies:
      - 🎯 全球直连
      - 🚀 节点选择
      - 🇺🇲 美国节点
      - 🇭🇰 香港节点
      - 🌀 手动切换
  - name: 🎯 全球直连
    type: select
    proxies:
      - DIRECT
  - name: 🛑 广告拦截
    type: select
    proxies:
      - REJECT
      - DIRECT
  - name: 🍃 应用净化
    type: select
    proxies:
      - REJECT
      - DIRECT
  - name: 🐟 漏网之鱼
    type: select
    proxies:
      - 🚀 节点选择
      - ♻️ 自动选择
      - 🌀 手动切换
      - 🎯 全球直连
  - name: 🇭🇰 香港节点
    type: select
    proxies:
      - 🇭🇰 香港01
      - 🇭🇰 香港02
      - 🇪🇸 香港TEST
  - name: 🇨🇳 台湾节点
    type: select
    proxies:
      - DIRECT
  - name: 🇸🇬 狮城节点
    type: select
    proxies:
      - DIRECT
  - name: 🇯🇵 日本节点
    type: select
    proxies:
      - 🇯🇵 日本01
      - 🇯🇵 日本02
      - 🇪🇸 日本TEST
  - name: 🇺🇲 美国节点
    type: select
    proxies:
      - 🇺🇲 美国01
      - 🇺🇲 美国02
  - name: 🇰🇷 韩国节点
    type: select
    proxies:
      - DIRECT
rules:
 - DOMAIN-SUFFIX,acl4.ssr,🎯 全球直连
 - DOMAIN-SUFFIX,ip6-localhost,🎯 全球直连
 - DOMAIN-SUFFIX,ip6-loopback,🎯 全球直连
 - DOMAIN-SUFFIX,lan,🎯 全球直连
 - DOMAIN-SUFFIX,local,🎯 全球直连
 - DOMAIN-SUFFIX,localhost,🎯 全球直连
 - IP-CIDR,10.0.0.0/8,🎯 全球直连,no-resolve
 - IP-CIDR,100.64.0.0/10,🎯 全球直连,no-resolve
 - IP-CIDR,127.0.0.0/8,🎯 全球直连,no-resolve
 - IP-CIDR,172.16.0.0/12,🎯 全球直连,no-resolve
 - IP-CIDR,192.168.0.0/16,🎯 全球直连,no-resolve
 - IP-CIDR,198.18.0.0/16,🎯 全球直连,no-resolve
 - IP-CIDR,224.0.0.0/4,🎯 全球直连,no-resolve
 - IP-CIDR6,::1/128,🎯 全球直连,no-resolve
 - IP-CIDR6,fc00::/7,🎯 全球直连,no-resolve
 - IP-CIDR6,fe80::/10,🎯 全球直连,no-resolve
 - IP-CIDR6,fd00::/8,🎯 全球直连,no-resolve
 - DOMAIN,instant.arubanetworks.com,🎯 全球直连
 - DOMAIN,setmeup.arubanetworks.com,🎯 全球直连
 - DOMAIN,router.asus.com,🎯 全球直连
 - DOMAIN-SUFFIX,hiwifi.com,🎯 全球直连
 - DOMAIN-SUFFIX,leike.cc,🎯 全球直连
 - DOMAIN-SUFFIX,miwifi.com,🎯 全球直连
 - DOMAIN-SUFFIX,my.router,🎯 全球直连
 - DOMAIN-SUFFIX,p.to,🎯 全球直连
 - DOMAIN-SUFFIX,peiluyou.com,🎯 全球直连
 - DOMAIN-SUFFIX,phicomm.me,🎯 全球直连
 - DOMAIN-SUFFIX,router.ctc,🎯 全球直连
 - DOMAIN-SUFFIX,routerlogin.com,🎯 全球直连
 - DOMAIN-SUFFIX,tendawifi.com,🎯 全球直连
 - DOMAIN-SUFFIX,zte.home,🎯 全球直连
 - DOMAIN-SUFFIX,tplogin.cn,🎯 全球直连
 - DOMAIN-SUFFIX,ol.epicgames.com,🎯 全球直连
 - DOMAIN-SUFFIX,dizhensubao.getui.com,🎯 全球直连
 - DOMAIN,dl.google.com,🎯 全球直连
 - DOMAIN-SUFFIX,googletraveladservices.com,🎯 全球直连
 - DOMAIN-SUFFIX,tracking-protection.cdn.mozilla.net,🎯 全球直连
 - DOMAIN,origin-a.akamaihd.net,🎯 全球直连
 - DOMAIN,xivanalysis.com,🎯 全球直连
 - DOMAIN,picanalysis.vivo.com.cn,🎯 全球直连
 - DOMAIN,picanalysis-auth.vivo.com.cn,🎯 全球直连
 - DOMAIN,fairplay.l.qq.com,🎯 全球直连
 - DOMAIN,livew.l.qq.com,🎯 全球直连
 - DOMAIN,vd.l.qq.com,🎯 全球直连
 - DOMAIN,analytics.strava.com,🎯 全球直连
 - DOMAIN,errlog.umeng.com,🎯 全球直连
 - DOMAIN,msg.umeng.com,🎯 全球直连
 - DOMAIN,msg.umengcloud.com,🎯 全球直连
 - DOMAIN,tracking.miui.com,🎯 全球直连
 - DOMAIN,app.adjust.com,🎯 全球直连
 - DOMAIN,bdtj.tagtic.cn,🎯 全球直连
 - DOMAIN,rewards.hypixel.net,🎯 全球直连
 - DOMAIN-KEYWORD,admarvel,🛑 广告拦截
 - DOMAIN-KEYWORD,admaster,🛑 广告拦截
 - DOMAIN-KEYWORD,adsage,🛑 广告拦截
 - DOMAIN-KEYWORD,adsensor,🛑 广告拦截
 - DOMAIN-KEYWORD,adservice,🛑 广告拦截
 - DOMAIN-KEYWORD,adsmogo,🛑 广告拦截
 - DOMAIN-KEYWORD,adsrvmedia,🛑 广告拦截
 - DOMAIN-KEYWORD,adsserving,🛑 广告拦截
 - DOMAIN-KEYWORD,adsystem,🛑 广告拦截
 - DOMAIN-KEYWORD,adwords,🛑 广告拦截
 - DOMAIN-KEYWORD,analysis,🛑 广告拦截
 - DOMAIN-KEYWORD,applovin,🛑 广告拦截
 - DOMAIN-KEYWORD,appsflyer,🛑 广告拦截
 - DOMAIN-KEYWORD,domob,🛑 广告拦截
 - DOMAIN-KEYWORD,duomeng,🛑 广告拦截
 - DOMAIN-KEYWORD,dwtrack,🛑 广告拦截
 - DOMAIN-KEYWORD,guanggao,🛑 广告拦截
 - DOMAIN-KEYWORD,omgmta,🛑 广告拦截
 - DOMAIN-KEYWORD,omniture,🛑 广告拦截
 - DOMAIN-KEYWORD,openx,🛑 广告拦截
 - DOMAIN-KEYWORD,partnerad,🛑 广告拦截
 - DOMAIN-KEYWORD,pingfore,🛑 广告拦截
 - DOMAIN-KEYWORD,socdm,🛑 广告拦截
 - DOMAIN-KEYWORD,supersonicads,🛑 广告拦截
 - DOMAIN-KEYWORD,usage,🛑 广告拦截
 - DOMAIN-KEYWORD,wlmonitor,🛑 广告拦截
 - DOMAIN-KEYWORD,zjtoolbar,🛑 广告拦截
 - DOMAIN-SUFFIX,09mk.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,100peng.com,🛑 广告拦截
 - DOMAIN-SUFFIX,114la.com,🛑 广告拦截
 - DOMAIN-SUFFIX,123juzi.net,🛑 广告拦截
 - DOMAIN-SUFFIX,138lm.com,🛑 广告拦截
 - DOMAIN-SUFFIX,17un.com,🛑 广告拦截
 - DOMAIN-SUFFIX,2cnt.net,🛑 广告拦截
 - DOMAIN-SUFFIX,3gmimo.com,🛑 广告拦截
 - DOMAIN-SUFFIX,3xx.vip,🛑 广告拦截
 - DOMAIN-SUFFIX,51.la,🛑 广告拦截
 - DOMAIN-SUFFIX,51taifu.com,🛑 广告拦截
 - DOMAIN-SUFFIX,51yes.com,🛑 广告拦截
 - DOMAIN-SUFFIX,600ad.com,🛑 广告拦截
 - DOMAIN-SUFFIX,6dad.com,🛑 广告拦截
 - DOMAIN-SUFFIX,70e.com,🛑 广告拦截
 - DOMAIN-SUFFIX,86.cc,🛑 广告拦截
 - DOMAIN-SUFFIX,8le8le.com,🛑 广告拦截
 - DOMAIN-SUFFIX,8ox.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,95558000.com,🛑 广告拦截
 - DOMAIN-SUFFIX,99click.com,🛑 广告拦截
 - DOMAIN-SUFFIX,99youmeng.com,🛑 广告拦截
 - DOMAIN-SUFFIX,a3p4.net,🛑 广告拦截
 - DOMAIN-SUFFIX,acs86.com,🛑 广告拦截
 - DOMAIN-SUFFIX,acxiom-online.com,🛑 广告拦截
 - DOMAIN-SUFFIX,ad-brix.com,🛑 广告拦截
 - DOMAIN-SUFFIX,ad-delivery.net,🛑 广告拦截
 - DOMAIN-SUFFIX,ad-locus.com,🛑 广告拦截
 - DOMAIN-SUFFIX,ad-plus.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,ad7.com,🛑 广告拦截
 - DOMAIN-SUFFIX,adadapted.com,🛑 广告拦截
 - DOMAIN-SUFFIX,adadvisor.net,🛑 广告拦截
 - DOMAIN-SUFFIX,adap.tv,🛑 广告拦截
 - DOMAIN-SUFFIX,adbana.com,🛑 广告拦截
 - DOMAIN-SUFFIX,adchina.com,🛑 广告拦截
 - DOMAIN-SUFFIX,adcome.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,ader.mobi,🛑 广告拦截
 - DOMAIN-SUFFIX,adform.net,🛑 广告拦截
 - DOMAIN-SUFFIX,adfuture.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,adhouyi.com,🛑 广告拦截
 - DOMAIN-SUFFIX,adinfuse.com,🛑 广告拦截
 - DOMAIN-SUFFIX,adirects.com,🛑 广告拦截
 - DOMAIN-SUFFIX,adjust.io,🛑 广告拦截
 - DOMAIN-SUFFIX,adkmob.com,🛑 广告拦截
 - DOMAIN-SUFFIX,adlive.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,adlocus.com,🛑 广告拦截
 - DOMAIN-SUFFIX,admaji.com,🛑 广告拦截
 - DOMAIN-SUFFIX,admin6.com,🛑 广告拦截
 - DOMAIN-SUFFIX,admon.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,adnyg.com,🛑 广告拦截
 - DOMAIN-SUFFIX,adpolestar.net,🛑 广告拦截
 - DOMAIN-SUFFIX,adpro.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,adpush.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,adquan.com,🛑 广告拦截
 - DOMAIN-SUFFIX,adreal.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,ads8.com,🛑 广告拦截
 - DOMAIN-SUFFIX,adsame.com,🛑 广告拦截
 - DOMAIN-SUFFIX,adsmogo.com,🛑 广告拦截
 - DOMAIN-SUFFIX,adsmogo.org,🛑 广告拦截
 - DOMAIN-SUFFIX,adsunflower.com,🛑 广告拦截
 - DOMAIN-SUFFIX,adsunion.com,🛑 广告拦截
 - DOMAIN-SUFFIX,adtrk.me,🛑 广告拦截
 - DOMAIN-SUFFIX,adups.com,🛑 广告拦截
 - DOMAIN-SUFFIX,aduu.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,advertising.com,🛑 广告拦截
 - DOMAIN-SUFFIX,adview.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,advmob.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,adwetec.com,🛑 广告拦截
 - DOMAIN-SUFFIX,adwhirl.com,🛑 广告拦截
 - DOMAIN-SUFFIX,adwo.com,🛑 广告拦截
 - DOMAIN-SUFFIX,adxmi.com,🛑 广告拦截
 - DOMAIN-SUFFIX,adyun.com,🛑 广告拦截
 - DOMAIN-SUFFIX,adzerk.net,🛑 广告拦截
 - DOMAIN-SUFFIX,agrant.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,agrantsem.com,🛑 广告拦截
 - DOMAIN-SUFFIX,aihaoduo.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,ajapk.com,🛑 广告拦截
 - DOMAIN-SUFFIX,allyes.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,allyes.com,🛑 广告拦截
 - DOMAIN-SUFFIX,amazon-adsystem.com,🛑 广告拦截
 - DOMAIN-SUFFIX,analysys.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,angsrvr.com,🛑 广告拦截
 - DOMAIN-SUFFIX,anquan.org,🛑 广告拦截
 - DOMAIN-SUFFIX,anysdk.com,🛑 广告拦截
 - DOMAIN-SUFFIX,appadhoc.com,🛑 广告拦截
 - DOMAIN-SUFFIX,appads.com,🛑 广告拦截
 - DOMAIN-SUFFIX,appboy.com,🛑 广告拦截
 - DOMAIN-SUFFIX,appdriver.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,appjiagu.com,🛑 广告拦截
 - DOMAIN-SUFFIX,applifier.com,🛑 广告拦截
 - DOMAIN-SUFFIX,appsflyer.com,🛑 广告拦截
 - DOMAIN-SUFFIX,atdmt.com,🛑 广告拦截
 - DOMAIN-SUFFIX,baifendian.com,🛑 广告拦截
 - DOMAIN-SUFFIX,banmamedia.com,🛑 广告拦截
 - DOMAIN-SUFFIX,baoyatu.cc,🛑 广告拦截
 - DOMAIN-SUFFIX,baycode.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,bayimob.com,🛑 广告拦截
 - DOMAIN-SUFFIX,behe.com,🛑 广告拦截
 - DOMAIN-SUFFIX,bfshan.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,biddingos.com,🛑 广告拦截
 - DOMAIN-SUFFIX,biddingx.com,🛑 广告拦截
 - DOMAIN-SUFFIX,bjvvqu.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,bjxiaohua.com,🛑 广告拦截
 - DOMAIN-SUFFIX,bloggerads.net,🛑 广告拦截
 - DOMAIN-SUFFIX,branch.io,🛑 广告拦截
 - DOMAIN-SUFFIX,bsdev.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,bshare.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,btyou.com,🛑 广告拦截
 - DOMAIN-SUFFIX,bugtags.com,🛑 广告拦截
 - DOMAIN-SUFFIX,buysellads.com,🛑 广告拦截
 - DOMAIN-SUFFIX,c0563.com,🛑 广告拦截
 - DOMAIN-SUFFIX,cacafly.com,🛑 广告拦截
 - DOMAIN-SUFFIX,casee.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,cdnmaster.com,🛑 广告拦截
 - DOMAIN-SUFFIX,chance-ad.com,🛑 广告拦截
 - DOMAIN-SUFFIX,chanet.com.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,chartbeat.com,🛑 广告拦截
 - DOMAIN-SUFFIX,chartboost.com,🛑 广告拦截
 - DOMAIN-SUFFIX,chengadx.com,🛑 广告拦截
 - DOMAIN-SUFFIX,chmae.com,🛑 广告拦截
 - DOMAIN-SUFFIX,clickadu.com,🛑 广告拦截
 - DOMAIN-SUFFIX,clicki.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,clicktracks.com,🛑 广告拦截
 - DOMAIN-SUFFIX,clickzs.com,🛑 广告拦截
 - DOMAIN-SUFFIX,cloudmobi.net,🛑 广告拦截
 - DOMAIN-SUFFIX,cmcore.com,🛑 广告拦截
 - DOMAIN-SUFFIX,cnxad.com,🛑 广告拦截
 - DOMAIN-SUFFIX,cnzz.com,🛑 广告拦截
 - DOMAIN-SUFFIX,cnzzlink.com,🛑 广告拦截
 - DOMAIN-SUFFIX,cocounion.com,🛑 广告拦截
 - DOMAIN-SUFFIX,coocaatv.com,🛑 广告拦截
 - DOMAIN-SUFFIX,cooguo.com,🛑 广告拦截
 - DOMAIN-SUFFIX,coolguang.com,🛑 广告拦截
 - DOMAIN-SUFFIX,coremetrics.com,🛑 广告拦截
 - DOMAIN-SUFFIX,cpmchina.co,🛑 广告拦截
 - DOMAIN-SUFFIX,cpx24.com,🛑 广告拦截
 - DOMAIN-SUFFIX,crasheye.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,crosschannel.com,🛑 广告拦截
 - DOMAIN-SUFFIX,ctrmi.com,🛑 广告拦截
 - DOMAIN-SUFFIX,customer-security.online,🛑 广告拦截
 - DOMAIN-SUFFIX,daoyoudao.com,🛑 广告拦截
 - DOMAIN-SUFFIX,datouniao.com,🛑 广告拦截
 - DOMAIN-SUFFIX,ddapp.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,dianjoy.com,🛑 广告拦截
 - DOMAIN-SUFFIX,dianru.com,🛑 广告拦截
 - DOMAIN-SUFFIX,disqusads.com,🛑 广告拦截
 - DOMAIN-SUFFIX,domob.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,domob.com.cn,🛑 广告拦截
 - DOMAIN-SUFFIX,domob.org,🛑 广告拦截
