port: 7890
socks-port: 7891
allow-lan: true
mode: Rule
log-level: info
external-controller: 127.0.0.1:9090
proxies:
 
  - {name: ๐ธ๐ฌ ็ฎๅ01, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: sg-gcore.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: sg-gcore.sharecentre.online}}}
  - {name: ๐ธ๐ฌ ็ฎๅ03, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: gcore-sg.cloudflare.quest}}}
  - {name: ๐ฏ๐ต ๆฅๆฌ01, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: jp1.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: jp1.sharecentre.online}}}
  - {name: ๐ฏ๐ต ๆฅๆฌ02, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: gcore-jp.cloudflare.quest}}}
  - {name: ๐ฉ๐ช ๅพทๅฝ01, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: de-1.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: de-1.sharecentre.online}}}
  - {name: ๐ฉ๐ช ๅพทๅฝ02, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: de-2.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: de-2.sharecentre.online}}}
  - {name: ๐ฌ๐ง ่ฑๅฝ01, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: uk-1.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: uk-1.sharecentre.online}}}
  - {name: ๐ฌ๐ง ่ฑๅฝ02, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: uk-2.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: uk-2.sharecentre.online}}}
  - {name: ๐ธ๐ฌ ็ฎๅ02, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: sg-1.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: sg-1.sharecentre.online}}}
  - {name: ๐บ๐ฒ ็พๅฝ01, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: us-dp2.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: us-dp2.sharecentre.online}}}
  - {name: ๐บ๐ฒ ็พๅฝ02, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: gcore-us.cloudflare.quest}}}
  - {name: "ๆฌๅๅฏจ01[Netflix]", server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: kh.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: kh.sharecentre.online}}}
  - {name: "๐น๐ท ๅ่ณๅถ01[Netflix]", server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: GCORE-TR.cloudflare.quest}}}
  - {name: ๐ป๐ณ ่ถๅ01, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: vn.cloudflare.quest}}}
  - {name: ๐ฎ๐ณ ๅฐๅบฆ01, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: gcore-in.cloudflare.quest}}}
  - {name: ๆณขๅฐ01, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: waw.cloudflare.quest}}}
  - {name: ๐ซ๐ท ๆณๅฝ01, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: france.cloudflare.quest}}}
  - {name: ๐ซ๐ท ๆณๅฝ02, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: fr.cloudflare.quest}}}
  - {name: ๐ณ๐ฑ ่ทๅฐ01, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: netherlands.cloudflare.quest}}}
  - {name: ๐ณ๐ฑ ่ทๅฐ02, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: scw.cloudflare.quest}}}
  - {name: ๐จ๐ฆ ๅ?ๆฟๅคง01, server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: ca-help.cloudflare.quest}}}
  - {name: "็ฑๆฒๅฐผไบ[Netflix]", server: no.aries.ovh, port: 2052, type: vmess, uuid: c6f7bae0-36d9-41a6-9962-e79156c899c6, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false, network: ws, ws-opts: {path: "/aries?ed=2048", headers: {Host: ee.cloudflare.quest}}}
  - {name: ไฝฌPๅฌ็้กน็ฎ, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: de-1.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: de-1.sharecentre.online}}}
  - {name: ไฝฌPๅฎขๆ?, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: de-1.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: de-1.sharecentre.online}}}
  - {name: ๆ้ซๅณฐ็ง4K, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: de-1.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: de-1.sharecentre.online}}}
  - {name: ไปฅไธ่็นไธบไธญ่ฝฌTest, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: de-1.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: de-1.sharecentre.online}}}
  - {name: ไธไฟ่ฏๆดปไน, server: cf-lt.sharecentre.online, port: 443, type: vmess, uuid: 20e92881-5fb4-4b05-bc77-57929476dc69, alterId: 0, cipher: auto, tls: true, skip-cert-verify: false, servername: de-1.sharecentre.online, network: ws, ws-opts: {path: /shirker, headers: {Host: de-1.sharecentre.online}}}
  - {name: ๐ช๐ธ ๆฅๆฌTEST, server: 20.210.192.230, port: 27692, type: vmess, uuid: 95bcf8c2-4b62-403f-afb3-bdbf171ddfcd, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false}
  - {name: ๐ช๐ธ ้ฆๆธฏTEST, server: 20.205.5.230, port: 26082, type: vmess, uuid: 41244752-c7d0-408d-d947-d9da6b501649, alterId: 0, cipher: auto, tls: false, skip-cert-verify: false}
proxy-groups:
  - name: ๐ ่็น้ๆฉ
    type: select
    proxies:
      - โป๏ธ ่ชๅจ้ๆฉ
      - ๐ญ๐ฐ ้ฆๆธฏ่็น
      - ๐จ๐ณ ๅฐๆนพ่็น
      - ๐ธ๐ฌ ็ฎๅ่็น
      - ๐ฏ๐ต ๆฅๆฌ่็น
      - ๐บ๐ฒ ็พๅฝ่็น
      - ๐ ๆๅจๅๆข
      - ๐ฏ ๅจ็็ด่ฟ
  - name: ๐ ๆๅจๅๆข
    type: select
    proxies:
   
      - ๐ธ๐ฌ ็ฎๅ01
      - ๐ธ๐ฌ ็ฎๅ03
      - ๐ฏ๐ต ๆฅๆฌ01
      - ๐ฏ๐ต ๆฅๆฌ02
      - ๐ฉ๐ช ๅพทๅฝ01
      - ๐ฉ๐ช ๅพทๅฝ02
      - ๐ฌ๐ง ่ฑๅฝ01
      - ๐ฌ๐ง ่ฑๅฝ02
      - ๐ธ๐ฌ ็ฎๅ02
      - ๐บ๐ฒ ็พๅฝ01
      - ๐บ๐ฒ ็พๅฝ02
      - ๆฌๅๅฏจ01[Netflix]
      - ๐น๐ท ๅ่ณๅถ01[Netflix]
      - ๐ป๐ณ ่ถๅ01
      - ๐ฎ๐ณ ๅฐๅบฆ01
      - ๆณขๅฐ01
      - ๐ซ๐ท ๆณๅฝ01
      - ๐ซ๐ท ๆณๅฝ02
      - ๐ณ๐ฑ ่ทๅฐ01
      - ๐ณ๐ฑ ่ทๅฐ02
      - ๐จ๐ฆ ๅ?ๆฟๅคง01
      - ็ฑๆฒๅฐผไบ[Netflix]
      - ไฝฌPๅฌ็้กน็ฎ
      - ไฝฌPๅฎขๆ?
      - ๆ้ซๅณฐ็ง4K
      - ไปฅไธ่็นไธบไธญ่ฝฌTest
      - ไธไฟ่ฏๆดปไน
      - ๐ช๐ธ ๆฅๆฌTEST
      - ๐ช๐ธ ้ฆๆธฏTEST

