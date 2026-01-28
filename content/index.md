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
This document provides comprehensive information about Amazons as an enterprise, covering its infrastructure, architecture, systems, networking, core technologies, terminology, and related components. [Amazons LTD](https://amazons.co.ke).

#links
  :::u-button
  ---
  to: /introduction/overview
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

  ```bash [amazons.config.rsc]{icon="i-heroicons-server"}
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

::u-page-section{class="dark:bg-neutral-950"}
#title
Amazons Enterprise Network Solutions

#links
  :::u-button
  ---
  color: neutral
  size: lg
  target: _blank
  to: /
  trailingIcon: i-lucide-arrow-right
  variant: subtle
  ---
  Client Portal
  :::

#features
  :::u-page-feature
  ---
  icon: i-lucide-zap
  ---
  #title
  High-Speed Fiber

  #description
  Symmetrical gigabit connectivity delivered over our dedicated fiber optic infrastructure with low latency.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-server
  ---
  #title
  MikroTik Powered

  #description
  Routing handled by enterprise-grade MikroTik CCR hardware running the latest RouterOS for maximum stability.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-shield-check
  ---
  #title
  Secure Perimeter

  #description
  Advanced firewall rules and active DDoS mitigation strategies to protect your internal network infrastructure.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-globe
  ---
  #title
  Global Peering

  #description
  Direct BGP peering with major content providers ensuring the fastest path to the data you need.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-activity
  ---
  #title
  99.9% Uptime SLA

  #description
  Fully redundant backbone architecture ensuring continuous availability for mission-critical operations.
  :::

  :::u-page-feature
  ---
  icon: i-lucide-headphones
  ---
  #title
  24/7 NOC Support

  #description
  Our Network Operations Center monitors infrastructure around the clock to prevent issues before they happen.
  :::
::