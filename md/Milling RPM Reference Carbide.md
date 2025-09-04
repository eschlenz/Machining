# Milling RPM Starting Points by Material (Carbide Tooling)

**Formula:** `RPM = (SFM × 4) ÷ Cutter Diameter (inches)`

> Carbide SFM ≈ 3× HSS (starting point; adjust per toolmaker guidance and rigidity).

| Material | SFM | 0.06" | 0.12" | 0.25" | 0.38" | 0.50" | 0.75" | 1.00" | 2.00" | 3.00" |
|----------|-----|-------|-------|-------|-------|-------|-------|-------|-------|-------|
| Aluminum 6061 | 900 | 57600 | 28800 | 14400 | 9600 | 7200 | 4800 | 3600 | 1800 | 1200 |
| Aluminum 7075 | 750 | 48000 | 24000 | 12000 | 8000 | 6000 | 4000 | 3000 | 1500 | 1000 |
| Brass (Free Cutting) | 600 | 38400 | 19200 | 9600 | 6400 | 4800 | 3200 | 2400 | 1200 | 800 |
| Bronze (Phosphor) | 300 | 19200 | 9600 | 4800 | 3200 | 2400 | 1600 | 1200 | 600 | 400 |
| Bronze (Aluminum) | 450 | 28800 | 14400 | 7200 | 4800 | 3600 | 2400 | 1800 | 900 | 600 |
| Copper | 450 | 28800 | 14400 | 7200 | 4800 | 3600 | 2400 | 1800 | 900 | 600 |
| Mild Steel (1018) | 300 | 19200 | 9600 | 4800 | 3200 | 2400 | 1600 | 1200 | 600 | 400 |
| Mild Steel (1045) | 270 | 17280 | 8640 | 4320 | 2880 | 2160 | 1440 | 1080 | 540 | 360 |
| Tool Steel (O1) | 180 | 11520 | 5760 | 2880 | 1920 | 1440 | 960 | 720 | 360 | 240 |
| Tool Steel (A2) | 150 | 9600 | 4800 | 2400 | 1600 | 1200 | 800 | 600 | 300 | 200 |
| Stainless (304) | 240 | 15360 | 7680 | 3840 | 2560 | 1920 | 1280 | 960 | 480 | 320 |
| Stainless (316) | 210 | 13440 | 6720 | 3360 | 2240 | 1680 | 1120 | 840 | 420 | 280 |
| Cast Iron (Gray) | 150 | 9600 | 4800 | 2400 | 1600 | 1200 | 800 | 600 | 300 | 200 |
| Cast Iron (Ductile) | 180 | 11520 | 5760 | 2880 | 1920 | 1440 | 960 | 720 | 360 | 240 |
| Titanium | 180 | 11520 | 5760 | 2880 | 1920 | 1440 | 960 | 720 | 360 | 240 |
| Plastics (Delrin) | 1200 | 76800 | 38400 | 19200 | 12800 | 9600 | 6400 | 4800 | 2400 | 1600 |
| Plastics (Nylon) | 900 | 57600 | 28800 | 14400 | 9600 | 7200 | 4800 | 3600 | 1800 | 1200 |
| Plastics (Acrylic) | 600 | 38400 | 19200 | 9600 | 6400 | 4800 | 3200 | 2400 | 1200 | 800 |

⚠ **Practical Note:** Mill RPM values are theoretical maximums based on surface speed and cutter diameter. In practice, your spindle’s max RPM, tool balance, and rigidity will often limit how fast you can run. If your machine tops out before the listed value, just run at its maximum safe RPM and adjust feed rate and depth of cut accordingly. Also account for flute count, coolant use, and tool manufacturer recommendations.