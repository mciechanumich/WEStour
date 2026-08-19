---
published: true
layout: default
position: 1
title: Temporary Kitchen
navstuff:
  link: wayne_route.md
  desc: WAYNE route
navstuff2:
  link: wayne_route_2firstfloor.html
  desc: WAYNE Route First Floor
audio: /audio/filler.mp3
#video
# comment: set this to false when we have some real pages working
description: The temporary kitchen tour stop.
#images:
#  - src: /image/fence300.jpg
#    alt: front fence
#extra:
---
<div>
<p>
The temporary kitchen stop.
</p>
</div>

<div>
<p>
<img src="image/drawing_firstfloor_w2.jpg" alt="first floor map"  width=300 class="framed-image">
</p>
</div>

<div>
Forward to
{% capture link_url %}{% link wayne_route_kitchen.md %}{% endcapture %}
<a href="{{ link_url | relative_url }}">
<button>
KITCHEN
</button>
</a>
</div>
