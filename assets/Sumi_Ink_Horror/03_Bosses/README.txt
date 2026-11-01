Two Bosses
==========

Thousand Hands Face: frame-by-frame boss with idle, slam, scream, hurt and defeat.
Shrine Guardian: cut-out puppet boss in separate parts (torso, belly, head, arm, hands)
with alternate states, spit teeth and a shockwave. Assemble it in your engine with the
pivots and sockets below; the arm is drawn once and mirrored for the other side.

Format: PNG with transparency (RGBA), unless noted. Pivots are in pixels from the
top-left corner of each frame or image. Sprite sheets are a single row of frames
of the listed size, left to right.

Thousand Hands Face
-------------------
thousand_hands_face/boss_idle: 3 frames, 1792x1152 px each, 5 fps, loop, pivot (896, 1060)
thousand_hands_face/boss_slam: 3 frames, 1792x1152 px each, 9 fps, once, pivot (896, 1060)
thousand_hands_face/boss_scream: 3 frames, 1792x1152 px each, 7 fps, once, pivot (896, 1060)
thousand_hands_face/boss_hurt: 2 frames, 1792x1152 px each, 6 fps, once, pivot (896, 1060)
thousand_hands_face/boss_defeat: 4 frames, 1792x1152 px each, 5 fps, once, pivot (896, 1060)

Shrine Guardian parts
---------------------
shrine_guardian/torso.png: 663x640 px, pivot (327, 612), sockets head (327, 57), right_shoulder (67, 162), left_shoulder (577, 162), belly (332, 447)
shrine_guardian/belly_closed.png: 380x420 px, pivot (190, 210)
shrine_guardian/belly_open.png: 380x420 px, pivot (190, 210)
shrine_guardian/head_neutral.png: 240x270 px, pivot (120, 244)
shrine_guardian/head_scream.png: 240x270 px, pivot (120, 244)
shrine_guardian/head_hurt.png: 240x270 px, pivot (120, 244)
shrine_guardian/head_defeated.png: 240x270 px, pivot (120, 244)
shrine_guardian/arm_right.png: 131x540 px, pivot (99, 30), wrist (74, 511)
shrine_guardian/hand_ground.png: 270x310 px, pivot (135, 40)
shrine_guardian/hand_eye_open.png: 270x310 px, pivot (135, 40)
shrine_guardian/hand_hurt.png: 270x310 px, pivot (135, 40)
shrine_guardian/hand_destroyed.png: 270x310 px, pivot (135, 40)
shrine_guardian/spit_teeth.png: 138x120 px, pivot (71, 61)
shrine_guardian/shockwave_0.png: 600x180 px, pivot (300, 148)
shrine_guardian/shockwave_1.png: 600x180 px, pivot (300, 148)
shrine_guardian/shockwave_2.png: 600x180 px, pivot (300, 148)
Shockwave: 3 frames at 12 fps, played once. The arm rotates around its pivot
(shoulder); hands hang from the wrist and stay upright.

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
