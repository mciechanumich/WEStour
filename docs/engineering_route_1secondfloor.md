---
published: true
layout: default
title: The ENGINEERING Route Second Floor
navstuff:
  link: engineering_route.md
  desc: ENGINEERING route
#audio: /audio/frontfenceplaceholder.mp3
#video
# comment: set this to false when we have some real pages working
description: Continue up the second floor to the third floor.
#images:
#  - src: /image/fence300.jpg
#    alt: front fence
#extra:
---
<div>
<p>
Continue up the second floor to the third floor.
</p>
</div>

<div>
<p>
<img src="image/drawing_secondfloor_w1.jpg" alt="second floor map"  width=300 class="framed-image">
</p>
</div>

<div>
Forward to
{% capture link_url %}{% link engineering_route_1thirdfloor.md %}{% endcapture %}
<a href="{{ link_url | relative_url }}">
<button>
THIRD FLOOR
</button>
</a>
</div>
