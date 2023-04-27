---
title: Home
layout: home
---

The guides on this site were created for and by the [Warframe Arbitrations][Discord] Discord community.

You are very welcome to join us, get notified about the current Arbitration, ask questions, discuss strategies, or find a group to run with.

https://discord.gg/placeholder

Currently we have the following guides:

{% for guide in site.guides %}
  [[guide.title]][[guide.url]]
{% endfor %}


[Discord]: https://discord.gg/placeholder