Vertical Climbing Backgrounds
=============================

Two vertical level sets that scroll upwards: the Well of Souls (old stone well with mist,
faces and a procession of spirits, with a top opening on the night sky) and the Hanging
Scroll (waterfall, sleeping faces on paper strips, faces among water and clouds, with an
ink waterfall at the top). Each set has three background layers that tile vertically, a
top piece and a sky, plus the platform pieces of that level at game scale.

Format: PNG with transparency (RGBA), unless noted. Pivots are in pixels from the
top-left corner of each frame or image. Sprite sheets are a single row of frames
of the listed size, left to right.

Well of Souls
-------------
well_of_souls/layers/background_1.png: 724x2108 px, tiles vertically
well_of_souls/layers/background_2.png: 724x2172 px, tiles vertically
well_of_souls/layers/background_3.png: 724x2108 px, tiles vertically
well_of_souls/layers/top.png: 729x2158 px
well_of_souls/layers/sky.png: 729x1100 px, opaque sky
well_of_souls/pieces/wall_tile.png: 112x480 px, tiles vertically, game scale
well_of_souls/pieces/ledge_short.png: 230x88 px, pivot (115, 0), game scale (half of the source drawing)
well_of_souls/pieces/ledge_medium.png: 327x86 px, pivot (164, 0), game scale (half of the source drawing)
well_of_souls/pieces/ledge_long.png: 425x91 px, pivot (212, 0), game scale (half of the source drawing)
well_of_souls/pieces/floor.png: 568x85 px, pivot (284, 0), game scale (half of the source drawing)

Hanging Scroll
--------------
hanging_scroll/layers/background_1.png: 724x2172 px, tiles vertically
hanging_scroll/layers/background_2.png: 1024x1472 px, tiles vertically
hanging_scroll/layers/background_3.png: 724x2108 px, tiles vertically
hanging_scroll/layers/top.png: 1024x1536 px
hanging_scroll/layers/sky.png: 1024x1100 px, opaque sky
hanging_scroll/pieces/scroll_edge_tile.png: 63x531 px, tiles vertically, game scale
hanging_scroll/pieces/flap_short.png: 213x104 px, pivot (106, 0), game scale (half of the source drawing)
hanging_scroll/pieces/flap_medium.png: 326x112 px, pivot (163, 0), game scale (half of the source drawing)
hanging_scroll/pieces/flap_long.png: 480x114 px, pivot (240, 0), game scale (half of the source drawing)
hanging_scroll/pieces/scroll_bottom.png: 527x59 px, pivot (264, 0), game scale (half of the source drawing)
hanging_scroll/pieces/scroll_rod.png: 530x117 px, pivot (265, 0), game scale (half of the source drawing)

Layer order, back to front: sky, background_1, background_2, background_3; the top piece
sits above background_1 where the level ends. Suggested parallax 0.1, 0.3 and 0.6.

Pieces at source resolution
---------------------------
The same pieces as above before the halving, plus the climbing hazards: pivots are top centre
for ledges, flaps, floor and the scroll parts (they hang or rest on their top edge), bottom
centre for the mask, the hand and the ink.
well_of_souls/pieces_fullres/wall_tile.png: 210x961 px, pivot (105, 0), tiles vertically
well_of_souls/pieces_fullres/ledge_short.png: 454x171 px, pivot (227, 0)
well_of_souls/pieces_fullres/ledge_medium.png: 650x169 px, pivot (325, 0)
well_of_souls/pieces_fullres/ledge_long.png: 845x177 px, pivot (422, 0)
well_of_souls/pieces_fullres/floor.png: 1132x166 px, pivot (566, 0)
hanging_scroll/pieces_fullres/scroll_edge_tile.png: 147x1134 px, pivot (73, 0), tiles vertically
hanging_scroll/pieces_fullres/flap_long.png: 974x236 px, pivot (487, 0)
hanging_scroll/pieces_fullres/flap_short.png: 435x212 px, pivot (217, 0)
hanging_scroll/pieces_fullres/flap_medium.png: 666x230 px, pivot (333, 0)
hanging_scroll/pieces_fullres/scroll_bottom.png: 1060x127 px, pivot (530, 0)
hanging_scroll/pieces_fullres/scroll_rod.png: 1063x245 px, pivot (531, 0)
hazards/noh_mask_intact.png: 353x249 px, pivot (176, 249)
hazards/noh_mask_cracked.png: 343x241 px, pivot (171, 241)
hazards/noh_mask_broken.png: 361x285 px, pivot (180, 285)
hazards/hand_trampoline_open.png: 414x142 px, pivot (207, 142)
hazards/hand_trampoline_mid.png: 385x215 px, pivot (192, 215)
hazards/hand_trampoline_closed.png: 397x230 px, pivot (198, 230)
hazards/ofuda_short.png: 307x179 px, pivot (153, 179)
hazards/ofuda_medium.png: 447x184 px, pivot (223, 184)
hazards/ofuda_long.png: 533x190 px, pivot (266, 190)
hazards/rising_ink_1.png: 504x202 px, pivot (252, 202)
hazards/rising_ink_2.png: 502x204 px, pivot (251, 204)
hazards/rising_ink_3.png: 504x209 px, pivot (252, 209)
The hand trampoline and the rising ink are 3-state sequences; the mask breaks in three steps.

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
