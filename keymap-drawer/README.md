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
`/ESC  Q  G  M  L  W  |  Y  F  U  B  ;    TAB
[NAVI] D  S  T  N  R  |  I  A  E  O  H    '
LSHFT  Z  X  C  V  J  |  K  P  ,  .  /    RSHFT
          CTRL  RET  GUI | SPC  BSPC  ALT
```

**Combos (layers 0+1):**
- Top+home row same col = `1`-`0`, shift+combo = `!` `@` `#` `$` `%` `^` `&` `*` `(` `)`

| Key | Behavior |
|-----|----------|
| `` ` ``/ESC | Tap = grave, hold = ESC |
| `[NAVI]` | Hold opens NAVI layer, release goes back |

## Layer 1: QWRT (QWERTY)

```
`/ESC  Q  W  E  R  T  |  Y  U  I  O  P    TAB
[NAVI] A  S  D  F  G  |  H  J  K  L  ;    '
LSHFT  Z  X  C  V  B  |  N  M  ,  .  /    RSHFT
          CTRL  RET  GUI | SPC  BSPC  ALT
```

Combos: same as CARP (top+home = 1-0)

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
| `->HUB` | Press to go to HUB layer |

## Layer 4: NAVI (Numbers, Nav, Symbols)

```
->HUB  1  2  3  4  5  |  +   [   UP   ]   *   =
  _    6  7  8  9  0  |  -   LEFT DOWN RIGHT /  \
LSHFT  _  _  _  _  _  |  _   _    _    _   _   RSHFT
          CTRL  RET  GUI | SPC  BSPC  ALT
```

| Key | Action |
|-----|--------|
| `->HUB` | Press to go to HUB layer |

## Layer 5: HUB (Media, BT, RGB, Layer Switch)

```
->CARP ->QWRT ->STEN ->FPS  _    PP   | BT0  BT1  BT2  BT3  BT4  BT_CLR
  _      _      _     _   SCRN+ VOL+  | HUE+ SAT+ BRT- [CLR]  _   OUT_TOG
  _      _      _     _   SCRN- VOL-  | HUE- SAT- BRT+  _     _    _
                    PREV  NEXT  MUTE   | TOG  EFR  EFF
```

| Key | Action |
|-----|--------|
| `OUT_TOG` | Toggle USB/BLE output |
| `HUE/SAT/BRT` | RGB underglow hue, saturation, brightness |
| `SCRN` | Display brightness (C_BRI_UP/DN) |
| `VOL` | Volume up/down |
| `PREV/NEXT` | Track previous/next |
| `PP` | Play/pause |
| `MUTE` | Mute toggle |
| `TOG` | RGB on/off |
| `EFF/EFR` | RGB effect next/previous |
| `[CLR]` | Tap-dance color presets: 1x=purple, 2x=white, 3x=red, 4x=blue, 5x=green |
