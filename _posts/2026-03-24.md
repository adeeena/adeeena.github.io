---
layout: post
title: Fun with lamps
---

Sunday's hack: The programmable lamp is alive, but the implementation is filthy.

The initial fumbling finally bore some fruit this Sunday: the programmable lamp is operational. It glows a warm red-orange when the machine is grinding through some logic, and shifts back to blue when idle.

![idle]({{ site.baseurl }}/images/2026-03/lamp-idle.png)

my baby is idle



![AI thonk]({{ site.baseurl }}/images/2026-03/thonk.png)

✨AI✨ says: thonk ![AI thonk]({{ site.baseurl }}/images/2026-03/thonk2.png)

But to be real: parsing raw logs to guess what's happening inside Copilots "brain" feels like a desperate(ish), dirty workaround. A kludge. After two days of tinkering, it seems viable for now—but "viable today" is a low bar. It works, but far from elegant.

While walking yesterday, I had a flashback to those high school movies where everyone is buzzing, waiting for some bullshit blog to drop the latest gossip, bullying, or intrigue about someone completely irrelevant (except for the main plot, obviously). Then someone sprints down the hallway screaming, "The blog updated, look!"

Was that person just sitting in the computer lab, obsessively hitting F5 for hours? It remains a total mystery.

However, the color lamp tinkering project is at [github](https://github.com/adeeena/slop-light).