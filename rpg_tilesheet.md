# RPG Tilesheet Atlas (auto-extracted)
**Source image:** `RPG tileset (full) - 300%.png`
**Image size:** 2048x2048 px  
**Coordinate system:** origin `(0,0)` is **top-left**; `x` increases right; `y` increases down.
**Rect format:** `(x, y, w, h)` in pixels.

## Notes for an LLM / Game Engine Integration
- Many assets are **multi-tile** (houses, large foliage clusters). Use the `anchor` hint for placing them consistently.
- Names are **systematic** (category + index) because the sheet mixes many asset types; you can rename them later if you want more semantic names.
- If you need strict tile coordinates for a tilemap (e.g., 16/32/48px tiles), ask and I’ll generate a **grid-based** atlas too.

## Sprites
| id | name | x | y | w | h | anchor | description |
|---:|---|---:|---:|---:|---:|---|---|
| 1 | `terrain_patch_01` | 0 | 0 | 192 | 288 | top-left | Large terrain/ground patch (likely multi-tile). |
| 2 | `prop_top_01` | 224 | 0 | 64 | 30 | bottom-center | Small prop/decoration (top section). |
| 3 | `decor_tiny_01` | 302 | 2 | 16 | 30 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 4 | `prop_top_02` | 330 | 2 | 76 | 94 | bottom-center | Small prop/decoration (top section). |
| 5 | `prop_top_03` | 426 | 2 | 12 | 94 | bottom-center | Small prop/decoration (top section). |
| 6 | `prop_top_04` | 458 | 2 | 76 | 30 | bottom-center | Small prop/decoration (top section). |
| 7 | `prop_top_05` | 554 | 2 | 76 | 94 | bottom-center | Small prop/decoration (top section). |
| 8 | `prop_top_06` | 650 | 2 | 12 | 94 | bottom-center | Small prop/decoration (top section). |
| 9 | `prop_top_07` | 682 | 2 | 76 | 30 | bottom-center | Small prop/decoration (top section). |
| 10 | `prop_top_08` | 778 | 2 | 76 | 94 | bottom-center | Small prop/decoration (top section). |
| 11 | `prop_top_09` | 874 | 2 | 12 | 94 | bottom-center | Small prop/decoration (top section). |
| 12 | `prop_top_10` | 906 | 2 | 76 | 30 | bottom-center | Small prop/decoration (top section). |
| 13 | `decor_tiny_02` | 200 | 8 | 18 | 18 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 14 | `decor_tiny_03` | 290 | 8 | 16 | 22 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 15 | `decor_tiny_04` | 166 | 16 | 14 | 12 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 16 | `decor_tiny_05` | 272 | 34 | 16 | 18 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 17 | `decor_tiny_06` | 458 | 34 | 12 | 30 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 18 | `decor_tiny_07` | 520 | 34 | 16 | 30 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 19 | `decor_tiny_08` | 682 | 34 | 12 | 30 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 20 | `decor_tiny_09` | 906 | 34 | 12 | 30 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 21 | `decor_tiny_10` | 260 | 36 | 10 | 10 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 23 | `decor_tiny_11` | 304 | 38 | 6 | 8 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 24 | `decor_tiny_12` | 492 | 38 | 10 | 24 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 25 | `decor_tiny_13` | 230 | 42 | 8 | 8 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 26 | `decor_tiny_14` | 196 | 44 | 10 | 8 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 27 | `decor_tiny_15` | 244 | 44 | 10 | 6 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 28 | `decor_tiny_16` | 294 | 44 | 6 | 8 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 29 | `decor_tiny_17` | 164 | 48 | 6 | 6 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 30 | `decor_tiny_18` | 210 | 48 | 8 | 8 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 31 | `decor_tiny_19` | 258 | 48 | 6 | 8 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 33 | `decor_tiny_20` | 238 | 50 | 8 | 6 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 34 | `decor_tiny_21` | 306 | 50 | 6 | 8 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 35 | `decor_tiny_22` | 268 | 52 | 8 | 8 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 38 | `decor_tiny_23` | 304 | 66 | 6 | 8 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 39 | `decor_tiny_24` | 452 | 66 | 24 | 28 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 40 | `decor_tiny_25` | 484 | 66 | 24 | 30 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 41 | `decor_tiny_26` | 294 | 68 | 6 | 8 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 42 | `decor_tiny_27` | 520 | 72 | 16 | 20 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 43 | `decor_tiny_28` | 232 | 74 | 16 | 14 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 44 | `decor_tiny_29` | 264 | 74 | 18 | 14 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 45 | `decor_tiny_30` | 310 | 74 | 6 | 8 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 46 | `decor_tiny_31` | 170 | 76 | 12 | 12 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 47 | `decor_tiny_32` | 204 | 78 | 10 | 8 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 48 | `decor_tiny_33` | 300 | 78 | 6 | 8 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 49 | `decor_tiny_34` | 292 | 84 | 6 | 8 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 50 | `decor_tiny_35` | 310 | 86 | 6 | 8 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 51 | `decor_tiny_36` | 678 | 86 | 20 | 36 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 52 | `decor_tiny_37` | 290 | 98 | 28 | 30 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 53 | `decor_tiny_38` | 322 | 98 | 28 | 30 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 54 | `decor_tiny_39` | 354 | 98 | 28 | 30 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 55 | `decor_tiny_40` | 386 | 98 | 28 | 30 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 56 | `decor_tiny_41` | 418 | 98 | 28 | 30 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 57 | `decor_tiny_42` | 450 | 98 | 28 | 30 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 58 | `decor_tiny_43` | 482 | 98 | 28 | 30 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 59 | `terrain_patch_02` | 768 | 98 | 224 | 286 | top-left | Large terrain/ground patch (likely multi-tile). |
| 60 | `prop_top_11` | 906 | 98 | 76 | 62 | bottom-center | Small prop/decoration (top section). |
| 61 | `decor_tiny_44` | 650 | 104 | 12 | 18 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 62 | `decor_tiny_45` | 266 | 106 | 14 | 14 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 63 | `decor_tiny_46` | 202 | 108 | 12 | 12 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 64 | `decor_tiny_47` | 234 | 110 | 12 | 10 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 69 | `decor_tiny_48` | 616 | 112 | 16 | 8 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 70 | `decor_tiny_49` | 710 | 112 | 20 | 10 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 71 | `prop_top_12` | 518 | 114 | 52 | 76 | bottom-center | Small prop/decoration (top section). |
| 76 | `prop_top_13` | 166 | 130 | 52 | 60 | bottom-center | Small prop/decoration (top section). |
| 77 | `prop_top_14` | 230 | 130 | 52 | 60 | bottom-center | Small prop/decoration (top section). |
| 78 | `decor_tiny_50` | 290 | 130 | 28 | 30 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 79 | `decor_tiny_51` | 322 | 130 | 28 | 30 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 80 | `decor_tiny_52` | 354 | 130 | 28 | 30 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 81 | `decor_tiny_53` | 386 | 130 | 28 | 30 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 82 | `decor_tiny_54` | 418 | 130 | 28 | 30 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 83 | `decor_tiny_55` | 450 | 130 | 28 | 30 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 84 | `decor_tiny_56` | 486 | 136 | 8 | 4 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 85 | `decor_tiny_57` | 488 | 138 | 18 | 18 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 86 | `prop_top_15` | 672 | 156 | 64 | 36 | bottom-center | Small prop/decoration (top section). |
| 87 | `prop_top_16` | 906 | 162 | 12 | 62 | bottom-center | Small prop/decoration (top section). |
| 88 | `decor_tiny_58` | 292 | 164 | 24 | 26 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 89 | `decor_tiny_59` | 324 | 164 | 24 | 26 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 90 | `decor_tiny_60` | 358 | 164 | 20 | 26 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 91 | `decor_tiny_61` | 392 | 164 | 16 | 26 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 92 | `decor_tiny_62` | 428 | 166 | 8 | 24 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 93 | `decor_tiny_63` | 450 | 168 | 28 | 20 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 94 | `decor_tiny_64` | 490 | 168 | 16 | 20 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 95 | `decor_tiny_65` | 644 | 170 | 24 | 20 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 97 | `decor_tiny_66` | 616 | 176 | 16 | 8 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 101 | `decor_tiny_67` | 450 | 192 | 30 | 30 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 102 | `prop_top_17` | 166 | 194 | 52 | 60 | bottom-center | Small prop/decoration (top section). |
| 103 | `prop_top_18` | 230 | 194 | 52 | 60 | bottom-center | Small prop/decoration (top section). |
| 104 | `decor_tiny_68` | 292 | 196 | 24 | 26 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 105 | `decor_tiny_69` | 324 | 196 | 24 | 26 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 106 | `prop_top_19` | 386 | 196 | 84 | 124 | bottom-center | Small prop/decoration (top section). |
| 107 | `decor_tiny_70` | 356 | 200 | 24 | 24 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 108 | `decor_tiny_71` | 420 | 200 | 24 | 24 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 109 | `prop_top_20` | 674 | 202 | 26 | 46 | bottom-center | Small prop/decoration (top section). |
| 110 | `decor_tiny_72` | 488 | 204 | 18 | 16 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 111 | `decor_tiny_73` | 710 | 214 | 20 | 34 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 112 | `prop_top_21` | 490 | 224 | 44 | 96 | bottom-center | Small prop/decoration (top section). |
| 113 | `decor_tiny_74` | 656 | 226 | 8 | 6 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 114 | `prop_top_22` | 298 | 230 | 76 | 90 | bottom-center | Small prop/decoration (top section). |
| 115 | `decor_tiny_75` | 646 | 230 | 16 | 18 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 119 | `decor_tiny_76` | 616 | 240 | 16 | 8 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 124 | `prop_top_23` | 174 | 258 | 36 | 60 | bottom-center | Small prop/decoration (top section). |
| 125 | `prop_top_24` | 238 | 258 | 36 | 60 | bottom-center | Small prop/decoration (top section). |
| 126 | `prop_top_25` | 554 | 262 | 76 | 58 | bottom-center | Small prop/decoration (top section). |
| 127 | `decor_tiny_77` | 130 | 264 | 28 | 22 | bottom-center | Tiny decor/particle/flower/stone (top section). |
| 128 | `prop_top_26` | 0 | 296 | 96 | 88 | bottom-center | Small prop/decoration (top section). |
| 129 | `prop_mid_01` | 174 | 322 | 36 | 60 | bottom-center | Prop/decoration near buildings (middle section). |
| 130 | `prop_mid_02` | 238 | 322 | 36 | 60 | bottom-center | Prop/decoration near buildings (middle section). |
| 131 | `house_small_01` | 462 | 336 | 132 | 140 | bottom-center | Small house/building (multi-tile). |
| 132 | `house_small_02` | 622 | 336 | 132 | 140 | bottom-center | Small house/building (multi-tile). |
| 133 | `building_block_01` | 0 | 384 | 448 | 288 | bottom-center | Large building block (multi-tile structure). |
| 134 | `house_small_03` | 768 | 398 | 160 | 144 | bottom-center | Small house/building (multi-tile). |
| 135 | `house_small_04` | 462 | 496 | 132 | 140 | bottom-center | Small house/building (multi-tile). |
| 136 | `house_small_05` | 622 | 496 | 132 | 140 | bottom-center | Small house/building (multi-tile). |
| 137 | `house_small_06` | 768 | 558 | 160 | 144 | bottom-center | Small house/building (multi-tile). |
| 138 | `prop_mid_03` | 962 | 576 | 30 | 32 | bottom-center | Prop/decoration near buildings (middle section). |
| 139 | `prop_mid_04` | 932 | 604 | 24 | 36 | bottom-center | Prop/decoration near buildings (middle section). |
| 140 | `prop_mid_05` | 966 | 618 | 20 | 22 | bottom-center | Prop/decoration near buildings (middle section). |
| 141 | `prop_mid_06` | 118 | 640 | 52 | 32 | bottom-center | Prop/decoration near buildings (middle section). |
| 142 | `building_block_02` | 320 | 654 | 448 | 176 | bottom-center | Large building block (multi-tile structure). |
| 143 | `prop_mid_07` | 956 | 660 | 40 | 38 | bottom-center | Prop/decoration near buildings (middle section). |
| 144 | `prop_mid_08` | 0 | 662 | 32 | 52 | bottom-center | Prop/decoration near buildings (middle section). |
| 145 | `prop_mid_09` | 64 | 662 | 32 | 52 | bottom-center | Prop/decoration near buildings (middle section). |
| 146 | `prop_mid_10` | 118 | 704 | 52 | 32 | bottom-center | Prop/decoration near buildings (middle section). |
| 147 | `house_small_07` | 768 | 718 | 160 | 144 | bottom-center | Small house/building (multi-tile). |
| 148 | `prop_mid_11` | 956 | 724 | 40 | 38 | bottom-center | Prop/decoration near buildings (middle section). |
| 149 | `prop_mid_12` | 118 | 768 | 52 | 32 | bottom-center | Prop/decoration near buildings (middle section). |
| 150 | `prop_mid_13` | 936 | 768 | 48 | 62 | bottom-center | Prop/decoration near buildings (middle section). |
| 151 | `prop_mid_14` | 0 | 784 | 32 | 70 | bottom-center | Prop/decoration near buildings (middle section). |
| 152 | `prop_mid_15` | 64 | 784 | 32 | 70 | bottom-center | Prop/decoration near buildings (middle section). |
| 153 | `prop_mid_16` | 116 | 832 | 56 | 32 | bottom-center | Prop/decoration near buildings (middle section). |
| 154 | `prop_mid_17` | 936 | 832 | 48 | 62 | bottom-center | Prop/decoration near buildings (middle section). |
| 155 | `building_block_03` | 320 | 846 | 608 | 176 | bottom-center | Large building block (multi-tile structure). |
| 156 | `prop_mid_18` | 118 | 896 | 52 | 32 | bottom-center | Prop/decoration near buildings (middle section). |
| 157 | `prop_mid_19` | 936 | 896 | 48 | 62 | bottom-center | Prop/decoration near buildings (middle section). |
| 158 | `prop_mid_20` | 0 | 912 | 32 | 70 | bottom-center | Prop/decoration near buildings (middle section). |
| 159 | `prop_mid_21` | 64 | 912 | 32 | 70 | bottom-center | Prop/decoration near buildings (middle section). |
| 160 | `prop_mid_22` | 112 | 960 | 64 | 64 | bottom-center | Prop/decoration near buildings (middle section). |
| 161 | `prop_mid_23` | 936 | 960 | 48 | 62 | bottom-center | Prop/decoration near buildings (middle section). |
| 162 | `foliage_cluster_01` | 2 | 1056 | 284 | 576 | bottom-center | Large foliage/tree cluster (multi-tile). |
| 163 | `foliage_cluster_02` | 288 | 1056 | 672 | 576 | bottom-center | Large foliage/tree cluster (multi-tile). |
| 164 | `foliage_cluster_03` | 482 | 1056 | 284 | 288 | bottom-center | Large foliage/tree cluster (multi-tile). |
| 165 | `tree_or_bush_01` | 768 | 1056 | 192 | 288 | bottom-center | Tree/bush chunk (multi-tile). |
