# Optional drawing and animation

Add one app to the original wedge-shaped Nintendo 2DS. [Junkdraw](https://github.com/randomouscrap98/3ds_junkdraw/tree/0.5.2) is an MIT-licensed stylus drawing app with page-based animation. This is a pilot setup pending a hands-on test on the original 2DS.

## Set up Homebrew Launcher

1. Charge the console. On a computer with internet access and an SD card reader, copy the full SD card to a backup folder before changing files. Keep the recovery backups the firmware guide creates.
2. Start at the live 3DS Hacks Guide. Use its existing firmware check for a secondhand console, then follow the branch for your model, region, system version, and firmware state. Finish the applicable steps until Homebrew Launcher opens. If the console shows something unexpected, stop and use the guide’s troubleshooting. [3DS Hacks Guide](https://3ds.hacks.guide/) · [Checking for custom firmware](https://3ds.hacks.guide/checking-for-cfw.html)

## Add Junkdraw

1. On your computer, download `3ds_junkdraw.3dsx` from the release assets. [Junkdraw 0.5.2](https://github.com/randomouscrap98/3ds_junkdraw/releases/tag/0.5.2)
2. Turn the 2DS all the way off before taking out the SD card. Copy the file into the top-level `3ds` folder so the path is `/3ds/3ds_junkdraw.3dsx`. Create the folder if it’s missing. Safely eject the card and put it back in the console.
3. Turn wireless off in **HOME Menu Settings → Wireless Communication**. Open **Homebrew Launcher** and choose **Junkdraw**. If it’s missing, check the file name and path on your computer. If it won’t run, stick with the [stock setup](QUICKSTART.md) and use the upstream project for app troubleshooting.

## Quick test on an original 2DS

Use Junkdraw 0.5.2 and a new test project. After copying the app to the SD card, keep **Wireless Communication** off for every check.

- [ ] **Install and launch.** Junkdraw appears in Homebrew Launcher and opens to a drawing canvas.
- [ ] **Draw.** Draw a ball with the stylus. Erase part of it and redraw it. The strokes and eraser respond where you touch.
- [ ] **Animate.** On a small canvas, hold **R** and press **Up** to advance a page. Draw the ball higher, then repeat for a third page. Press **Start** and use the animation controls. All three frames play in order and loop.
- [ ] **Save and reopen offline.** Save as `Ball test`, close the app, and power the 2DS off and back on. Confirm wireless is still off. Relaunch Junkdraw, load `Ball test`, and check that all three drawings are intact and the loop still plays.

Pass when all four boxes are checked. If one fails, note the step, your Junkdraw and Luma3DS versions, and what appeared on screen.

To remove the app, power off the console and delete only `/3ds/3ds_junkdraw.3dsx` from the SD card. Back up any drawings before removing their save data.
