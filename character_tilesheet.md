# Character Tilesheet (Elf)
- Source image: `Elf_idle (32x48).png`
- Image size: 128x192 px
- Grid: 4 columns × 4 rows
- Frame size: 32x48 px
- Coordinate system: `x,y` are pixel coordinates from the **top-left** of the spritesheet.

## Frames (coordinates + meaning)
| id | name | row | col | x | y | w | h | description |
|---:|---|---:|---:|---:|---:|---:|---:|---|
| 0 | `down_0` | 0 | 0 | 0 | 0 | 32 | 48 | Facing down/front. Neutral pose / idle frame A. |
| 1 | `down_1` | 0 | 1 | 32 | 0 | 32 | 48 | Facing down/front. Idle bob / step frame B. |
| 2 | `down_2` | 0 | 2 | 64 | 0 | 32 | 48 | Facing down/front. Neutral pose / idle frame C. |
| 3 | `down_3` | 0 | 3 | 96 | 0 | 32 | 48 | Facing down/front. Idle bob / step frame D. |
| 4 | `left_0` | 1 | 0 | 0 | 48 | 32 | 48 | Facing left. Neutral pose / idle frame A. |
| 5 | `left_1` | 1 | 1 | 32 | 48 | 32 | 48 | Facing left. Idle bob / step frame B. |
| 6 | `left_2` | 1 | 2 | 64 | 48 | 32 | 48 | Facing left. Neutral pose / idle frame C. |
| 7 | `left_3` | 1 | 3 | 96 | 48 | 32 | 48 | Facing left. Idle bob / step frame D. |
| 8 | `right_0` | 2 | 0 | 0 | 96 | 32 | 48 | Facing right. Neutral pose / idle frame A. |
| 9 | `right_1` | 2 | 1 | 32 | 96 | 32 | 48 | Facing right. Idle bob / step frame B. |
| 10 | `right_2` | 2 | 2 | 64 | 96 | 32 | 48 | Facing right. Neutral pose / idle frame C. |
| 11 | `right_3` | 2 | 3 | 96 | 96 | 32 | 48 | Facing right. Idle bob / step frame D. |
| 12 | `up_0` | 3 | 0 | 0 | 144 | 32 | 48 | Facing up/back. Neutral pose / idle frame A. |
| 13 | `up_1` | 3 | 1 | 32 | 144 | 32 | 48 | Facing up/back. Idle bob / step frame B. |
| 14 | `up_2` | 3 | 2 | 64 | 144 | 32 | 48 | Facing up/back. Neutral pose / idle frame C. |
| 15 | `up_3` | 3 | 3 | 96 | 144 | 32 | 48 | Facing up/back. Idle bob / step frame D. |

## Direction mapping
- **Row 0 (y=0..47):** `down/*` (front-facing)
- **Row 1 (y=48..95):** `left/*`
- **Row 2 (y=96..143):** `right/*`
- **Row 3 (y=144..191):** `up/*` (back-facing)

## Suggested animation clips (for movement/idle)
These clips assume the 4 frames in each row form a looping cycle.

### Idle (standing)
- `idle_down`: frames `[down_0, down_1, down_2, down_3]` (loop, ~6–8 fps)
- `idle_left`: frames `[left_0, left_1, left_2, left_3]` (loop, ~6–8 fps)
- `idle_right`: frames `[right_0, right_1, right_2, right_3]` (loop, ~6–8 fps)
- `idle_up`: frames `[up_0, up_1, up_2, up_3]` (loop, ~6–8 fps)

### Walk/Run (moving)
If you don’t have a separate walk sheet, you can reuse the same 4-frame cycle at a higher speed.

- `walk_down`: frames `[down_0, down_1, down_2, down_3]` (loop, ~10–12 fps)
- `walk_left`: frames `[left_0, left_1, left_2, left_3]` (loop, ~10–12 fps)
- `walk_right`: frames `[right_0, right_1, right_2, right_3]` (loop, ~10–12 fps)
- `walk_up`: frames `[up_0, up_1, up_2, up_3]` (loop, ~10–12 fps)

## Implementation notes for an LLM
- Treat **direction** as the last non-zero movement vector (`up/down/left/right`).
- When speed ≈ 0 → play `idle_<dir>`; when speed > 0 → play `walk_<dir>`.
- If your engine supports it, use a consistent pivot (e.g., bottom-center) when rendering to avoid jitter.
