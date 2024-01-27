---
layout: post
title:  "Welcome!"
date: 2024-01-27
categories: [homelab] #tags and categories needs to be lowercase and separated by commas
tags: [IT]
---

# Welcome

**Hello world**, this is my first Jekyll blog post.

```bash
sudo apt get update
```
```yaml
  prowlarr:
    image: lscr.io/linuxserver/prowlarr:latest
    container_name: prowlarr
    environment:
      - PUID=1000
      - PGID=1000
      - TZ=Australia/Melbourne
    volumes:
      - /home/mediaadmin/dockerdata/arrs/data/prowlarr:/config
    ports:
      - 9696:9696
    restart: unless-stopped
```
