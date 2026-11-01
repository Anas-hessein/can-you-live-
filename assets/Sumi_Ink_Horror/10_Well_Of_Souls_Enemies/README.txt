Well of Souls Enemies
=====================

Enemies for a vertical climbing level: the Stitched Twins (walk, attack, hit and defeat),
the Sack of Faces (hanging, falling, bursting) and two cut-out kits to assemble in your
engine: a centipede (head open or closed, body segments with legs, tail, curled ball) and
an eye cluster with seven sockets and four eye states plus a tear projectile.

Format: PNG with transparency (RGBA), unless noted. Pivots are in pixels from the
top-left corner of each frame or image. Sprite sheets are a single row of frames
of the listed size, left to right.

Animations
----------
stitched_twins/twins_walk: 4 frames, 640x480 px each, 6 fps, loop, pivot (320, 440)
stitched_twins/twins_attack: 3 frames, 640x480 px each, 7 fps, once, pivot (320, 440)
stitched_twins/twins_hit_defeat: 2 frames, 640x480 px each, 4 fps, once, pivot (320, 440)
sack_of_faces/sack_hanging: 3 frames, 640x480 px each, 4 fps, loop, pivot (320, 30)
sack_of_faces/sack_falling: 1 frame, 640x480 px each, 1 fps, once, pivot (320, 30)
sack_of_faces/sack_burst: 3 frames, 640x480 px each, 6 fps, once, pivot (320, 440)

Centipede and eye cluster parts
-------------------------------
centipede/head_closed.png: 360x260 px, pivot (320, 100)
centipede/head_open.png: 360x260 px, pivot (320, 100)
centipede/segment_legs_front.png: 380x260 px, pivot (25, 100), sockets rear (340, 100)
centipede/segment_legs_back.png: 380x260 px, pivot (25, 100), sockets rear (340, 100)
centipede/tail.png: 550x260 px, pivot (25, 100)
centipede/curled_ball.png: 480x440 px, pivot (240, 410)
eye_cluster/base.png: 420x400 px, pivot (210, 20), sockets eye_1 (69, 150), eye_2 (285, 150), eye_3 (181, 208), eye_4 (30, 234), eye_5 (319, 243), eye_6 (117, 300), eye_7 (250, 298)
eye_cluster/eye_closed.png: 144x144 px, pivot (72, 64)
eye_cluster/eye_open.png: 144x144 px, pivot (72, 64)
eye_cluster/eye_tear.png: 144x144 px, pivot (72, 64)
eye_cluster/eye_hurt.png: 144x144 px, pivot (72, 64)
eye_cluster/tear_projectile.png: 64x96 px, pivot (32, 48)
Segments chain from the pivot of one to the rear socket of the previous; the head goes
first and the tail last. Eyes sit on the base's sockets by their pivot.

Licence
-------
You may use these assets in any number of projects, commercial or not, including games sold
on any platform, and modify them as you need. You may not redistribute or resell the asset
files themselves, modified or not, as assets, templates or in any other collection. Credit
is appreciated but not required.

Origin
------
The source drawings were generated with ChatGPT (gpt-image) from the author's prompts and
references, then cut out, aligned, scaled and assembled into frames, sheets and parts by
script. Stores that ask for it should have this pack marked as AI-generated content.
