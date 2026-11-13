# Optional drawing and animation

Add one app to the original wedge-shaped Nintendo 2DS. [Junkdraw](https://github.com/randomouscrap98/3ds_junkdraw/tree/0.5.2) is an MIT-licensed stylus drawing app with page-based animation. This is a pilot setup pending a hands-on test on the original 2DS.

Want a chat to guide you one step at a time? Use the [guided setup walkthrough](WALKTHROUGH.md).

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

## Optional: Pick a HOME Menu theme

After Junkdraw passes, preview two themes and let your kid pick. “Mario or Yoshi?” is plenty. A bright stock color works too.

1. **Use a theme you already have.** Open **HOME Menu Settings → Change Theme** and pick it. [Nintendo’s theme instructions](https://en-americas-support.nintendo.com/app/answers/detail/a_id/12420/p/172)
2. **Or use a custom theme.** If Anemone3DS is available from your [homebrew setup](https://3ds.hacks.guide/finalizing-setup.html), copy a compatible theme ZIP you’re allowed to use to `/themes/` on the SD card with the console powered off. Open Anemone3DS, preview the theme, and use its normal single-theme install. [Anemone3DS instructions](https://github.com/astronautlevel2/Anemone3DS/wiki/Usage)
3. **Check it.** Restart with wireless off. Confirm the theme is still there and Junkdraw opens. To go back, choose a stock theme under **Change Theme**. If the theme menu or your chosen theme is unavailable, skip this step.
