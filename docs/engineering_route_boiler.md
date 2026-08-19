---
published: true
layout: default
position: 1
title: Boiler
# audio: /audio/filler.mp3
#video
# comment: set this to false when we have some real pages working
description: The boiler tour stop.
#images:
#  - src: /image/fence300.jpg
#    alt: front fence
#extra:
---
<div>
<p>
The boiler tour stop.
</p>
</div>

<div>
<p>
<img src="image/drawing_basement_e2.jpg" alt="basement map"  width=300 class="framed-image">
</p>
</div>

<div>
Forward to
{% capture link_url %}{% link engineering_route_electrical.md %}{% endcapture %}
<a href="{{ link_url | relative_url }}">
<button>
ELECTRICAL
</button>
</a>
</div>
