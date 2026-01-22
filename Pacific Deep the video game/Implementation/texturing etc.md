## Covering the Ground and Floor, Initial Ideas

Basic procedural texture that fills all the area, without repetition or tiling, yet not consuming too much memory.

When removing walls and rock, that texture uncovers.


## Path and polygon based areas

Textured areas controlled by paths (splines etc.) and polygons.

Swappable materials at any time.

When paths intersect, the texture adapts to make intersection (e.g. if bordered by rocky tiles the tiles form a proper intersection...)

Implementation idea for the road type of things with borders.
 - Two layers:
  1. top: The middle of the roads - pebbles, tiles, etc.
  2. bottom: Border of the roads - rocks, etc.
 - When two such roads intersect the bottom layer doesn't interfere, creating nice intersections

Catmull-Rom splines


## Water covered areas and rivers

Polygon based tool which has an automatic smooth transition from shallow to deeper waters.





spline roads rivers etc.
https://www.youtube.com/watch?v=NqS7novuN_k&ab_channel=UnrealMadeEasy

https://www.reddit.com/r/unrealengine/comments/12ok5nb/best_method_for_runtime_procedural_splinebased/

https://discussions.unity.com/t/road-system-for-unity-based-on-the-current-spline-package-and-the-terrain-system/1664437

https://forums.unrealengine.com/t/tutorial-create-a-procedural-spline-road-tool-in-blueprints-4-part-video-series/7760

https://vincentgeffroy.itch.io/splines-for-roads-and-rivers

https://www.youtube.com/watch?v=tQ49FnQjIHk&ab_channel=HojDee
