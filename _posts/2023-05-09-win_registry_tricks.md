---
title: Windows Registry tips&tricks
author: "Hansjoerg Morandell"
date: 2023-05-09 11:55:00 +0800
categories: [Technical, Howto]
tags: [tricks, regedit]
mermaid: true
---

Start Remote Registry service on an endpoint

```powershell
sc config RemoteRegistry start=auto
sc start RemoteRegistry
```
You can configure the service start-up type from the command line, this are the possible values:

```
auto		service automatically started at boot time, even if no user logs on
boot		device driver loaded by the boot loader
demand		service that must be manually started (the default)
disabled	service that can’t be started
system		service started during kernel initialization
```


