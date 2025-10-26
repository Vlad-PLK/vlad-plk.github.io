---
layout: post
title: "Born2BeRoot or not to be ?"
date: 2025-09-08 20:00:00 +0000
categories: [devops, linux, server-administration]
tags: [debian, virtualbox, server-hardening, wordpress, system-administration]
---

# Rebuilding Born2BeRoot

**Focus Area**: Linux Server Administration

---

## 🎯 Context & Objective

Setting up a Debian VM as a proper server environment. Not just repeating the 42 School project—adding real-world security practices and DevOps approaches.

## ✅ Work Recap & Achievements

**VM Setup**: Fresh Debian install on VirtualBox with appropriate resources and network config.

**Security Hardening**: Applied security measures—firewall setup, SSH hardening, monitoring tools.

**WordPress Deployment**: Got a full WordPress stack running with lighttpd, MariaDB, and PHP.

**What I built:**
- Debian server with UFW firewall and secure SSH
- Working WordPress site (lighttpd instead of Apache)
- Basic monitoring setup
- Server configuration documented

## 🧗 Challenges & Struggles

**Service Integration**: Getting lighttpd, MariaDB, and PHP to cooperate took some troubleshooting. Each had specific config requirements.

**Security Balance**: Finding the sweet spot between locked-down security and actually being able to use the server. Some security settings broke things initially.

**VM Resources**: Had to be careful with resource allocation to keep everything running smoothly.

## 📚 Key Learnings & Progress

**What I learned:**
- Debian system administration and package management
- Web server security (UFW, SSH keys)
- LAMP stack deployment (lighttpd variant)
- systemd for managing services

**Thinking Like an Admin**: Started balancing security, performance, and maintainability—important for managing infrastructure.

## ⏭️ Next Steps & Closing Thoughts

This was a step up from just command-line work. Managing multiple services that interact with each other requires more careful thinking.

Seeing the WordPress stack come together on infrastructure I built was pretty cool.

Next: diving deeper into networking and system internals. Want to understand how data flows through networks and how Linux actually manages resources. 🛡️