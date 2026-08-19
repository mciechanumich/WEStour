---
published: true
layout: default
title: The Balcony
audio: /audio/filler.mp3
#video
# comment: set this to false when we have some real pages working
description: The third floor balcony
#images:
#  - src: /image/fence300.jpg
#    alt: front fence
#extra:
---
<div>
<p>
The third floor balcony.
</p>
</div>

<div>
<p>
<img src="image/drawing_thirdfloor_e1.jpg" alt="third floor map"  width=300 class="framed-image">
</p>
</div>

<div>
Forward to
{% capture link_url %}{% link engineering_route_2secondfloor.md %}{% endcapture %}
<a href="{{ link_url | relative_url }}">
<button>
SECOND FLOOR
</button>
</a>
</div>
