---
published: true
layout: default
title: The First Floor
navstuff:
  link: engineering_route.md
  desc: ENGINEERING route
#audio: /audio/frontfenceplaceholder.mp3
#video
# comment: set this to false when we have some real pages working
description: The first floor
#images:
#  - src: /image/fence300.jpg
#    alt: front fence
#extra:
---
<div>
<p>
Down on first floor. Proceed to kitchen tour stop.
</p>
</div>

<div>
<p>
<img src="image/drawing_firstfloor_e2b.jpg" alt="first floor map"  width=300 class="framed-image">
</p>
</div>

<div>
Forward to
{% capture link_url %}{% link engineering_route_tempkitchen.md %}{% endcapture %}
<a href="{{ link_url | relative_url }}">
<button>
TEMPORARY KITCHEN
</button>
</a>
</div>
