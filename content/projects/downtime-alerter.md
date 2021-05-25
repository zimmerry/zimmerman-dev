---
title: "Downtime Alerter"
date: 2021-01-23T22:38:17-07:00
draft: false
author: "Ryan Zimmerman"
tags: ["personal-project"]
showToc: false
description: "Sends a text message when a website is inaccessible"
cover:
    image: "/downtime.png"
    alt: "Downtime Alerter Screenshot"
disableShare: true
---
[GitHub](https://github.com/zimmerry/downtime-alerter)

Downtime Alerter was built using Node.js and Handlebars for the web interface,
and uses TextBelt to sent a text message using an SMTP relay.

I created it to have a simple method of receiving notifications when components
of my homelab have issues or go down.