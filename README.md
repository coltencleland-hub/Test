# Kishi / CRT Consumer — 50 Overlays

50 original RetroArch landscape overlays: 28 material finishes, 10 cinematic environments, 6 anime backgrounds, and 6 pixel art scenes. Each keeps the original 3120 × 1504 canvas, curved gameplay opening, and ten utility buttons.

[Download all 50 overlays in one ZIP](https://github.com/coltencleland-hub/Test/archive/refs/heads/kishi-overlays.zip)

[Preview all 50 designs](all-50-preview.jpg) · [See the theme-switching button](theme-switching-preview.jpg)

## Install

1. Download the ZIP and extract the entire archive on your phone.
2. Keep the two cycling presets, `theme-button.png`, and all numbered theme folders together. Preserve the folder structure.
3. In RetroArch, open **Settings → On-Screen Display → On-Screen Overlay → Overlay Preset**.
4. Select `cycle-realistic-38.cfg` for the material and cinematic themes, or `cycle-all-50.cfg` for the full collection.
5. Tap **THEME >**, above **FAST >>**, to switch artwork. The last theme wraps back to the first.

For one fixed design, select `overlay.cfg` inside its numbered theme folder. Keep that file beside its `overlay.png`. Loading a cycling preset can take longer because it loads multiple images.

## Keep the original fit

Use the settings that already fit your phone:

- Display Overlay: **ON**
- Auto-Scale Overlay: **ON**
- Landscape Scale: **1.00**
- Overlay Opacity: **1.00**
- Hide Overlay When Controller Connected: **OFF**
- Aspect adjustment, offsets, and separations: **0**

Keep `crt-consumer` enabled with **Core Provided** GBA 3:2 aspect and **Integer Scale OFF**. The original shader fit uses Curvature X **0.03**, Curvature Y **0.04**, Corner **0.03**, and Smoothness **400**. These overlays preserve that opening and game scale; they do not require a viewport or shader adjustment.

## Controls

| Left side | Right side |
| --- | --- |
| SAVE — save state | FAST >> — toggle fast forward |
| LOAD — load state | REWIND — hold to rewind |
| SLOT + — next state slot | PAUSE — toggle pause |
| SLOT − — previous state slot | MENU — RetroArch menu |
| SHOT — screenshot | MUTE — toggle audio mute |

Rewind requires **Rewind Support** in RetroArch. Kishi controls and touch utilities can work together with **Hide Overlay When Controller Connected OFF**. The presets do not change controller bindings. You can optionally bind RetroArch’s **Next Overlay** hotkey to an unused Kishi button.

## Validation

Local CLI checks verified all 50 images against the original transparency mask and button pixels, preserved the original ten touch descriptors, and checked both cycling presets for complete loops and valid file references. The files and theme switching have **not been retested on the phone**.
