---
weight: 12002
title: "Overview of the Tutorials Page"
description: "Step-by-Step Guides for Navigating Higher Education"
icon: cast_for_education
date: 2025-01-03T15:00:00+03:00
---

{{< alert text="Have a question? We're happy to assist. Feel free to [email us](mailto:support@highereduspot.com)." />}}

sudo -i or sudo -s (root)
aaPanel
wget -O install.sh http://www.aapanel.com/script/install-ubuntu_6.0_en.sh && sudo bash install.sh aapanel

cloudflared
wget -q https://github.com/cloudflare/cloudflared/releases/latest/download/cloudflared-linux-amd64.deb && dpkg -i cloudflared-linux-amd64.deb

cloudflared tunnel login (or cloudflared login)

cloudflared tunnel create <NAME>

nano ~/.cloudflared/config.yml
url: http://localhost
tunnel: 84f59edb-2019-45eb-83f3-06862cfa700b
credentials-file: /root/.cloudflared/84f59edb-2019-45eb-83f3-06862cfa700b.json

cloudflared tunnel run

CNAME Record: 84f59edb-2019-45eb-83f3-06862cfa700b.cfargotunnel.com


---


sudo -i or sudo -s (root)

aaPanel
URL=https://www.aapanel.com/script/install_7.0_en.sh && if [ -f /usr/bin/curl ];then curl -ksSO "$URL" ;else wget --no-check-certificate -O install_7.0_en.sh "$URL";fi;bash install_7.0_en.sh aapanel

cloudflared
wget -q https://github.com/cloudflare/cloudflared/releases/latest/download/cloudflared-linux-amd64.deb && dpkg -i cloudflared-linux-amd64.deb

cloudflared tunnel login (or cloudflared login)

cloudflared tunnel create <NAME>

nano ~/.cloudflared/config.yml
url: http://localhost
tunnel: 84f59edb-2019-45eb-83f3-06862cfa700b
credentials-file: /root/.cloudflared/84f59edb-2019-45eb-83f3-06862cfa700b.json

cloudflared tunnel run

CNAME Record: code-code-code-code-code.cfargotunnel.com