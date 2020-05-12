---
title: Vigilante 
layout: role
alignment: town
enabled: yes
description: shoots people
---

The Vigilante holds a gun and is able to shoot one person each night. If the person shot is town aligned, then The Vigilante will commit suicide right before the lynch of the night after. Else, if the target was a neutral or mafia aligned role, then The Vigilante will not commit suicide. This role is not told any information about its target. The Vigilante's shot is concurrent with mafia shot.

{% capture interactions %}
Vigilante > Mafia A, Mafia A > Vigilante;
Mafia A dies, Vigilante dies;
Vigilante shots and mafia shots are concurrent.

---
Vigilante > Executioner;
Executioner dies, Vigilante does not suicide;
Executioner is a neutral aligned role

{% endcapture %}

{% endcapture %} {% include interactions.html content=interactions %}

Check out [Contributing]({{ site.baseurl }}{% link information/contributing.md %}) to see how to fill in this role!
