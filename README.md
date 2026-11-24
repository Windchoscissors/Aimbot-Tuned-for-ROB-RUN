# Aimbot Tuned for ROB RUN

Download: soon

A build of the aim module that ships already tuned for the city maps: tight FOV, chest first, no head snapping at range.

## Shipped defaults

| Value | Set to | Why |
| --- | --- | --- |
| fov | 5 | corners are short, a wide FOV pulls off-target |
| smooth | 5.0 | readable movement indoors |
| bone | chest | head only helps below 15 m |
| visible | on | plenty of thin cover |
| mode | hold | output stays clean |

## Tune further

1. Play one raid with the defaults untouched.
2. Only if the crosshair lags: smoothing down by 1.
3. Only if it snaps: smoothing up by 1.
4. Switch bone to head for building rotations, back to chest outdoors.

## Install

1. Extract to its own folder
2. `loader.exe` as administrator
3. Start ROB RUN
4. INSERT, bind the key

## FAQ

**Why chest default?** Head tracking at 40 m looks robotic. Chest keeps the curve believable.

**Does it have ESP?** No, aim only. Pair it with a visual build if needed.

**Sensitivity changes?** Retune smoothing afterwards.

## Troubleshooting

No overlay: borderless. No menu: admin. Nothing attaches: loader before game.

Windows 10/11, Steam, EAC, offsets refresh after patches.
