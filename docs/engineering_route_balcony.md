---
published: true
layout: default
title: The Balcony
audio: /audio/balcony.mp3
navstuff:
  link: engineering_route.md
  desc: ENGINEERING route
navstuff2:
  link: engineering_route_1thirdfloor.md
  desc: ENGINEERING route third floor
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
<p>Link to
{% capture link_url %}{% link balcony_txt.md %}{% endcapture %}
<a href="{{ link_url | relative_url }}" target="_BLANK">
transcript
</a>.
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
