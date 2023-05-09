---
title: Useful Nextcloud commands
author: Hansjoerg Morandell
date: 2023-05-08 11:33:00 +0800
categories: [Technical, Howto]
tags: [docker, nextcloud]
math: true
mermaid: true
---

If you add some files not via the WebUI, you can wait for the cron to run otherwise you can use the following command to force a rescan of the file folder

connect to the docker image. The -u switch tells which user to connect to (sudo)
Replace <IMAGE_ID> with the actual ID of your image:
```bash
docker exec -u33 -it <IMAGE_ID> bash
```

start the scan for all users:
```bash
./occ files:scan --all
```

this will output (on success):
```bash
www-data@IMAGE_ID:~/html$ ./occ files:scan --all

Starting scan for user 1 out of 1 (USERNAME)
+---------+-------+--------------+
| Folders | Files | Elapsed time |
+---------+-------+--------------+
| 11      | 80    | 00:00:00     |
+---------+-------+--------------+
```

