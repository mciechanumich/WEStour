---
published: true
layout: default
position: 1
title: WAYNE Route Second Floor
#audio: /audio/frontfenceplaceholder.mp3
#video
# comment: set this to false when we have some real pages working
description: The second floor.
#images:
#  - src: /image/fence300.jpg
#    alt: front fence
#extra:
---
<div>
<p>
The second floor.
</p>
</div>

<div>
<p>
<img src="image/drawing_basement_w.jpg" alt="basement map"  width=300 class="framed-image">
</p>
</div>

<div>
Forward to
{% capture link_url %}{% link wayne_route_thirdfloor.md %}{% endcapture %}
<a href="{{ link_url | relative_url }}">
<button>
THIRD FLOOR
</button>
</a>
</div>
