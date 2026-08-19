---
published: true
layout: default
title: The Third Floor
navstuff:
  link: engineering_route.md
  desc: ENGINEERING route
#audio: /audio/frontfenceplaceholder.mp3
#video
# comment: set this to false when we have some real pages working
description: The second floor
#images:
#  - src: /image/fence300.jpg
#    alt: front fence
#extra:
---
<div>
<p>
Down through second floor.
</p>
</div>

<div>
<p>
<img src="image/drawing_secondfloordown_s1.jpg" alt="third floor map"  width=300 class="framed-image">
</p>
</div>

<div>
Forward to
{% capture link_url %}{% link engineering_route_2firstfloor.md %}{% endcapture %}
<a href="{{ link_url | relative_url }}">
<button>
FIRST FLOOR
</button>
</a>
</div>
