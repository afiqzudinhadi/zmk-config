# Keymap Reference

## Key Positions

```
 0  1  2  3  4  5  |  6  7  8  9 10 11
12 13 14 15 16 17  | 18 19 20 21 22 23
24 25 26 27 28 29  | 30 31 32 33 34 35
         36 37 38  | 39 40 41
```

## Layer 0: CARP (Carpalx QGMLWY)

```
`      Q  G  M  L  W  |  Y  F  U  B  ;    ->HUB
[HUB]  D  S  T  N  R  |  I  A  E  O  H    '
LSHFT  Z  X  C  V  J  |  K  P  ,  .  /    RSHFT
        [RGB]  CTRL  GUI | SPC  ALT  MUTE/PP
```

**Combos (layers 0+1):**
- Top+home row same col = `1`-`0`, shift+combo = `!` `@` `#` `$` `%` `^` `&` `*` `(` `)`
- G+M (W+E on QWRT) = ESC
- S+T (S+D on QWRT) = TAB
- U+B (I+O on QWRT) = BSPC
- E+O (K+L on QWRT) = ENTER

| Key | Behavior |
|-----|----------|
| `[HUB]` | Hold opens HUB layer, release goes back |
| `[RGB]` | Tap-dance: 1x=toggle, 2x=effect fwd, 3x=effect rev |
| `MUTE/PP` | Tap mute, hold play/pause |

## Layer 1: QWRT (QWERTY)

```
`      Q  W  E  R  T  |  Y  U  I  O  P    ->HUB
[HUB]  A  S  D  F  G  |  H  J  K  L  ;    '
LSHFT  Z  X  C  V  B  |  N  M  ,  .  /    RSHFT
        [RGB]  CTRL  GUI | SPC  ALT  MUTE/PP
```

Combos: same as CARP (top+home = 1-0, W+E = ESC, S+D = TAB, I+O = BSPC, K+L = ENTER)

## Layer 2: STEN (Placeholder)

Reserved for steno engine. Currently all `&none`.

## Layer 3: FPS (WASD shifted right for ortho)

```
1/ESC  2     Q  [W]  E/3   R/4  | 5    6    7    8    9    ->HUB
TAB    SHFT [A] [S] [D]    F    | _    _    _    _    _    _
M/ALT  Z     X   C   V     G    | _    _    _    _    _    _
              T     CTRL  SPC   | _    _    _
```

| Key | Behavior |
|-----|----------|
| `1` | Tap = 1, hold = ESC |
| `E` | Tap = E, hold = 3 |
| `R` | Tap = R, hold = 4 |
| `M` | Tap = M, hold = ALT |

## Layer 4: HUB (Utility — BT, RGB, Media, Nav)

```
BT_CLR BT0    BT1    BT2    BT3     BT4     | +      [     UP    ]     *    =
OUT_TOG HUE+  SAT+   BRT+   SCRN+   VOL+    | -      LEFT  DOWN  RIGHT /    \
LSHFT  HUE-   SAT-   BRT-   SCRN-   VOL-    | ->CARP ->QWRT ->STEN ->FPS [CLR] RSHFT
             [RGB]    CTRL   GUI              | SPC    ALT   MUTE/PP
```

| Key | Action |
|-----|--------|
| `OUT_TOG` | Toggle USB/BLE output |
| `HUE/SAT/BRT` | RGB underglow hue, saturation, brightness |
| `SCRN` | Display brightness (C_BRI_UP/DN) |
| `VOL` | Volume up/down |
| `[RGB]` | Tap-dance: 1x=toggle, 2x=effect fwd, 3x=effect rev |
| `[CLR]` | Tap-dance color presets: 1x=purple, 2x=white, 3x=red, 4x=blue, 5x=green |
| `MUTE/PP` | Tap mute, hold play/pause |
