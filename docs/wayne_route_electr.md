---
published: true
layout: default
position: 1
title: Electrical
audio: /audio/filler.mp3
navstuff:
  link: wayne_route.md
  desc: WAYNE route
navstuff2:
  link: wayne_route_basement.html
  desc: WAYNE Route Basement
#video
# comment: set this to false when we have some real pages working
description: The electrical tour stop.
#images:
#  - src: /image/fence300.jpg
#    alt: front fence
#extra:
---
<div>
<p>
The electrical stop.
</p>
</div>

<div>
<p>
<img src="image/drawing_basement_w.jpg" alt="basement map"  width=300 class="framed-image">
</p>
</div>

<div>
Forward to
{% capture link_url %}{% link wayne_route_boiler.md %}{% endcapture %}
<a href="{{ link_url | relative_url }}">
<button>
BOILER
</button>
</a>
</div>
