---
published: true
layout: default
title: Front Fence
audio: /audio/fence.mp3
navstuff:
  link: engineering_route.md
  desc: ENGINEERING route
navstuff2:
  link: engineering_route_exterior.md
  desc: ENGINEERING route exterior
#video
# comment: set this to false when we have some real pages working
description: The front fence tour stop.
#images:
#  - src: /image/fence300.jpg
#    alt: front fence
#extra:
---
<div>
<p>
The front fence tour stop.
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
{% capture link_url %}{% link engineering_route_dumpster.md %}{% endcapture %}
<a href="{{ link_url | relative_url }}">
<button>
DUMPSTER
</button>
</a>
</div>
