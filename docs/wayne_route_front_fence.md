---
published: true
layout: default
position: 1
title: Front Fence
navstuff:
  link: wayne_route.md
  desc: WAYNE route
navstuff2:
  link: wayne_route_1exterior.md
  desc: WAYNE Route Exterior
audio: /audio/fence.mp3
#video
# comment: set this to false when we have some real pages working
description: The Front Fence tour stop.
#images:
#  - src: /image/fence300.jpg
#    alt: front fence
#extra:
---
<div>
<p>
The Front Fence tour stop.
</p>
</div>

<div>
<p>Link to
{% capture link_url %}{% link fence_txt.md %}{% endcapture %}
<a href="{{ link_url | relative_url }}" target="_BLANK">
transcript
</a>.
</p>
</div>

<div>
<p>
<img src="image/drawing_exterior.jpg" alt="exterior map"  width=300 class="framed-image">
</p>
</div>

<div>
Forward to 
{% capture link_url %}{% link wayne_route_dumpster.md %}{% endcapture %}
<a href="{{ link_url | relative_url }}">
<button>
DUMPSTER
</button>
</a>
</div>
