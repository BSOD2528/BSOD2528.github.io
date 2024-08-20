---
layout: post
media: /assets/images/blog-6.gif
toc: true
tags: tech hardware
anchor: false
sidenav: false
---

Exactly what I meant, here is a small post on how I suffered for two entire days with Windows🤡.

Okay so initally I bought a Western Digital 2TB hard disk as I was assembling my PC, but it broke cause it fell down. Now now, don't go on ranting how I broke it. Please😔.
As an alternative I was using my dad's **2TB Seagate External HDD**.

# Stage 1
Well, as per recommendations (people I know on discord) HD Sentinel was installed. Initially my HDD health was at 50%. As time went by it decreased slowly.

I stored stuff like games, photos, videos, and documents from college, etc. 

# Stage 2
As time passed, HD Sentinel started throwing out errors saying your HDD is dying. Buy a new disk / back up data immediately. I had 96 days of life for the past 5 to 6 months.

# Stage 3
- Destroyer of Worlds (see what I did there haha)

One fine day, Windows started to literally become unusable. This was two days immediately after I changed my PSU as it got worn out due to frequent power outages. Thanks to
the government for that.

Windows would be literally "unusable". Nothing would happen. Before this, I started to luckily back up most of the data on to my new 2TB SSD. Its not my data, cause family's
is more important as its just media. Mine are music files etc.

Upon logging in after restarting the PC, the desktop would take literally 20 minutes to load. Once loaded, nothing would work. I was discombobulated how Windows 11 could crash
by not using for 1 week. FYI, I was on developer channel in the Insider Program.

# Remedy
I reinstalled Windows, however I went to Windows 10 cause I was sick and tired. However, I had my HDD unplugged and didn't notice. Once I plugged it back in to copy the remaining
data. The same issues happened. THAT's WHEN MY BIG BRAIN CLICKED.

I booted into Arch Linux and used <span class="cb">ntfs-3g</span> to copy the remaining data.

# TLDR
- Monitor health of Storage Devices
- If old, back up and change the device
- Else, enjoy living.

{%
    include paginate.html
    back="/pages/blog.html"
    _back="Blogs"
%}