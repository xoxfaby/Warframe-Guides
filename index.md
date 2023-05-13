---
title: Home
layout: home
---

The guides on this site were created for and by the [Warframe Arbitrations](http://discord.gg/PJtNphPh6v) Discord community.

You are very welcome to join us, get notified about the current Arbitration, ask questions, discuss strategies, or find a group to run with.

[http://discord.gg/s42BwXmPwX](http://discord.gg/s42BwXmPwX)

Currently we have the following guides:

{% for guide in site.guides %}
  [{{guide.title}}]({{guide.url}})
{% endfor %}

