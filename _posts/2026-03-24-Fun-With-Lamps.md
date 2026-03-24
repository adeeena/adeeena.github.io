---
layout: post
title: Fun with lamps
---

Sunday's hack: The programmable lamp is alive, but the implementation is filthy.

The initial fumbling finally bore some fruit this Sunday: the programmable lamp is operational. It glows a warm red-orange when the machine is grinding through some logic, and shifts back to blue when idle.

![idle]({{ site.baseurl }}/images/2026-03/lamp-idle.png)

![AI thonk]({{ site.baseurl }}/images/2026-03/thonk.png)

But to be real: parsing raw logs to guess what's happening inside Copilot’s "brain" feels like a desperate, dirty workaround. A kludge. After two days of tinkering, it seems viable for now—but "viable today" is a low bar. It works, but far from elegant.