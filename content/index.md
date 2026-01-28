---
seo:
  title: Amazons LTD Docs 
  description: Make a Difference with Excellence.
---

::u-page-hero{class="dark:bg-gradient-to-b from-neutral-900 to-neutral-950"}
---
orientation: horizontal
---
#top
:hero-background

#title
Make a Difference with Excellence [Amazons]{.text-primary}.

#description
This document provides comprehensive information about Amazon as an enterprise, covering its infrastructure, architecture, systems, networking, core technologies, terminology, and related components. [Amazons LTD](https://amazons.co.ke).

#links
  :::u-button
  ---
  to: /getting-started
  size: xl
  trailing-icon: i-lucide-arrow-right
  ---
  Get started
  :::

  :::u-button
  ---
  icon: i-simple-icons-github
  color: neutral
  variant: outline
  size: xl
  to: https://amazons.co.ke
  target: _blank
  ---
  View
  :::

#default
  :::prose-pre
  ---
  code: |
    /ip address
    add address=192.168.88.1/24 interface=ether1 network=192.168.88.0 comment="WAN"
    add address=10.0.0.1/24 interface=ether2 network=10.0.0.0 comment="LAN"

    /ip dns
    set servers=8.8.8.8,1.1.1.1 allow-remote-requests=yes

    /ip route
    add distance=1 gateway=192.168.88.1
  filename: amazons.config.rsc
  ---

  ```ts [nuxt.config.ts]
    /ip address
    add address=192.168.88.1/24 interface=ether1 network=192.168.88.0 comment="WAN"
    add address=10.0.0.1/24 interface=ether2 network=10.0.0.0 comment="LAN"

    /ip dns
    set servers=8.8.8.8,1.1.1.1 allow-remote-requests=yes

    /ip route
    add distance=1 gateway=192.168.88.1
  ```
  :::
::