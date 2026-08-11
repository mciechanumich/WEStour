---
published: true
layout: default
position: 1
title: Dumpster
audio: /audio/filler.mp3
#video
# comment: set this to false when we have some real pages working
description: The dumpster tour stop.
#images:
#  - src: /image/fence300.jpg
#    alt: front fence
#extra:
---
<div>
<p>
The dumpster tour stop.
</p>
</div>

<div>
<p>
<img src="image/drawing_exterior.jpg" alt="exterior map"  width=300 class="framed-image">
</p>
</div>

<div>
Forward to 
{% capture link_url %}{% link wayne_route_ext_electr.md %}{% endcapture %}
<a href="{{ link_url | relative_url }}">
<button>
EXTERIOR ELECTRICAL
</button>
</a>
</div>
