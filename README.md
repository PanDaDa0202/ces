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
 
