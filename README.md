# Ray Direction v2.0

Something common in my Houdini workflows is projecting geo or finding intersections between lines and surfaces.
I wrapped some of that in an HDA which you may find useful, too. Not a replacement for the Ray SOP.
Just great convenience which can complement a Ray SOP workflow.

It calculates (ray) direction vectors in 1 of 2 different modes: Origin or Direction

New to v2.0 is the feature to use the local transform axis of any object as the direction source.
That way you can match the direction of a directional light for example.

It takes Ray geo, Collision geo (optional), and Occlusion geo (optional) as inputs.
Neat mask attribute output available for the collision geo on Output 2.

I hope you'll find it useful! Cheers!
