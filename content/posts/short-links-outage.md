---
date: '2026-08-13T09:32:35-07:00'
title: Short Links Outage
author: Coach Juan
summary: 'I woke up to a notification that our Shortlink service is down (when you open some of our short links that use `rwf.sh` in them).'
images:
  - cover.png
---

{{< notice warning >}}
Active Incident with `rwf.sh` Shortlinks
{{< /notice >}}

This morning, I woke up to a notification that our Shortlink service is down (when you open some of our short links that use `rwf.sh` in them). I thought maybe the server was having issues but after review I learned that the datacenter our server is hosted on is experiencing an outage. (Apparently they lost power? )

---

**If you need access to things like registration or more, send us an [email](https://www.redwoodswonderforge.org/#contact) or DM us on [Facebook](https://www.facebook.com/RedwoodsWonderForge).**

If you need access to our calendars:

- [Classes Google Calendar](https://calendar.google.com/calendar/embed?src=c_8553ddf3a29d2ecfce26063ec438788046e72220d7d1a29eaa9c22c2b294257c%40group.calendar.google.com&ctz=America%2FLos_Angeles)
- [FLL & FTC Google Calendar](https://calendar.google.com/calendar/embed?src=c_ea96b391a567dfb4bf817633f3b000ee18da7bc22445ee9da35811bdb4768569%40group.calendar.google.com&ctz=America%2FLos_Angeles)

---

I've been making a lot of changes to the website, mainly trying to make it simpler for us to maintain and for people to access it. Ironically, moving off of our internal server introduced us the whims of lazy wild electrons. 😂

I'll update this once our services are back up. Additionally, the web services we use can be checked on our 
[Status Page](https://stats.uptimerobot.com/bj2aXI2GT3).

## Updates

### Update 14:27 PM

Looks like my server is back but officially, the data center incident isn't completely resolved. This might look like odd behavior where links sometimes work and sometimes don't. I'll update again soon.

### Update 12:22 PM

Did some more research and found out that the [datacenter having issues is this one located in Phoenix](https://status.phoenixnap.com/incidents/dnjp5pfv2mmh). Very interesting to find this out. I don't know how I feel that our stuff is hosted in a desert and is being brought down by cooling issues. Just doesn't sit right with me. I'm going to noodle on this - maybe bring it up with the [FTC team](https://25682.redwoodswonderforge.org/). This is their planet now and I'm curious what they think about us taxing the resources of remote desert infrastructure.

For now, I'm paying attention to the thread and waiting for my server to come back up soon.

### Update 10:30 AM

I needed a place to document events and updates for RWF expecially once I migrated the website away from Ghost. Something that I can update easily but not have to worry about maintenance. This incident forced me to bring up _something_. I created this service and added this first post. I'll keep it updated as I learn things. 

I discussed with the Executive Director volunteer extradordinaire Ciri regarding moving the service to a totally different server or should we just wait. We decided to wait - we're not a +1k user technology company, it's fine. I just like to [cosplay as a sysadmin sometimes](https://www.jeffgeerling.com/blog/2022/cosplaying-sysadmin/).