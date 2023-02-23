# CLASHV2
config clash v2
generat proxy provide di sub.bonds.id
contoh : 


proxies:
  - name: HTTP Injector
    server: www.skillacademy.com
    port: 443
    type: trojan
    password: 59211ae0-af3b-11ed-93ae-1239d0255272
    skip-cert-verify: true
    sni: sg-2.test3.net
    network: ws
    ws-opts:
      path: /howdy
      headers:
        Host: sg-2.test3.net
    udp: true
