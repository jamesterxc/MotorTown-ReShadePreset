This preset fixes Motor Town’s unstable exposure system, eliminating daytime glare, nighttime darkness, and random brightness spikes.
It also ensures truck cosmetics (paint, decals, accessories) remain visible.

Installation Guide
1. Install ReShade
Download the official ReShade installer from:

https://reshade.me

Run the installer before continuing.

2. Download the Preset
Place the preset file ReShadePreset.ini into your Motor Town directory or anywhere you prefer to load it from.

3. Select Motor Town in ReShade
When the ReShade installer opens:
Scroll through the detected games list.
Select:
MotorTown-Win64-Shipping.exe
If it does not appear automatically, click Browse and navigate to:
Code
Steam\steamapps\common\MotorTownBehindTheWheel\
Click Next.

4. Choose Rendering API
Select:
DirectX 10/11/12
Motor Town uses DirectX 11, so this is the correct option.
Click Next.
5. Import the Preset
At the bottom of the ReShade window, click Browse and select:

ReShadePreset.ini

This is the only file you need to load.
Do not change any other settings unless you intend to customize the preset.

6. Required In‑Game Brightness Setting
To ensure stable exposure, set:
Settings → Display → Brightness → 100
Motor Town’s exposure system is tied directly to the brightness slider.
Brightness at 100 prevents extreme exposure jumps that cause glare or darkness.

Note:  
The main menu and loading screens may appear washed out.
This is normal — gameplay lighting will be stable.

7. Launch Motor Town
Start the game and press Home to open ReShade.
Your preset will already be active.

Troubleshooting
If truck cosmetics disappear:
Reinstall ReShade
Re‑import ReShadePreset.ini
This resolves missing paint, decals, and accessories.

Results
No more daytime glare
No more nighttime blindness
Smooth exposure transitions
Cosmetics remain visible
Zero performance impact

Stable lighting with brightness at 100
If you want, I can also generate:
A shorter “Quick Install” section


