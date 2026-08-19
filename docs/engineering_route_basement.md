---
published: true
layout: default
title: The Basement
navstuff:
  link: engineering_route.md
  desc: ENGINEERING route
#audio: /audio/frontfenceplaceholder.mp3
#video
# comment: set this to false when we have some real pages working
description: The basement
#images:
#  - src: /image/fence300.jpg
#    alt: front fence
#extra:
---
<div>
<p>
Down in basement. Proceed to boiler tour stop.
</p>
</div>

<div>
<p>
<img src="image/drawing_basement_e2.jpg" alt="third floor map"  width=300 class="framed-image">
</p>
</div>

<div>
Forward to
{% capture link_url %}{% link engineering_route_boiler.md %}{% endcapture %}
<a href="{{ link_url | relative_url }}">
<button>
BOILER
</button>
</a>
</div>
