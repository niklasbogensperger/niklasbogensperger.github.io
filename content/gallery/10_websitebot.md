---
title: "websiteBot"
subtitle: "Python & PostgreSQL"
weight: 10
date: "2024-05-01T12:00:00+02:00"
image: "gallery/10_websitebot.png"
alt: "websiteBot"
github:
    repo: "hoengggroup/websitebot"
    showInfo: true
    showButtons: true
draft: false
---


Telegram bot written in Python, which monitors a given website for changes using an efficient from-scratch implementation of a diff-like difference tracker. Upon detecting changes, it sends a message via the Telegram bot [`@websiteBot_bot`&nbsp;{{< svg "static/link_modal_alt.svg" >}}](https://t.me/websiteBot_bot)&MediumSpace;to any people who subscribed to updates about a given website.

The project consists of several notable parts:
- the "frontend" is written in Python using the [python-telegram-bot&nbsp;{{< svg "static/link_modal.svg" >}}](https://github.com/python-telegram-bot/python-telegram-bot)&MediumSpace;library
- the difference algorithm is also implemented in Python and utilizes dynamic programming techniques
- data is persisted in a PostgreSQL database and interacted with using the [psycopg3&nbsp;{{< svg "static/link_modal.svg" >}}](https://github.com/psycopg/psycopg)&MediumSpace;library
- continuous operation, server networking and VPN setup, and restarts after fatal execution errors are implemented via a shell script that is registered as a `systemd` module

Created together with [Tassilo Schwarz&nbsp;{{< svg "static/link_modal.svg" >}}](https://tassilo-schwarz.com/).
