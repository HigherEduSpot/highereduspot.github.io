---
weight: 12002
title: "Turn a Computer into a Web Server"
description: "Turn a Computer into a Web Server"
icon: cast_for_education
date: 2025-01-03T15:00:00+03:00
---

{{< alert text="Have a question? We're happy to assist. Feel free to [email us](mailto:support@highereduspot.com)." />}}

### Root

sudo -i or sudo -s (root)

### aaPanel
URL=https://www.aapanel.com/script/install_7.0_en.sh && if [ -f /usr/bin/curl ];then curl -ksSO "$URL" ;else wget --no-check-certificate -O install_7.0_en.sh "$URL";fi;bash install_7.0_en.sh aapanel

### Cloudflare Tunnel
wget -q https://github.com/cloudflare/cloudflared/releases/latest/download/cloudflared-linux-amd64.deb && dpkg -i cloudflared-linux-amd64.deb

cloudflared tunnel login (or cloudflared login)

cloudflared tunnel create -NAME-

nano ~/.cloudflared/config.yml

url: http://localhost

tunnel: code-code-code-code-code

credentials-file: /root/.cloudflared/code-code-code-code-code.json

cloudflared tunnel run

CNAME Record: code-code-code-code-code.cfargotunnel.com