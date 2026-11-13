![Level 1-1. Bring back the magic of your first Nintendo. Less scrolling. More imagination. A translucent red original 2DS shows a platform game and a stylus drawing.](assets/level-1-1-hero-translucent-red.png)

# Level 1-1

**Bring back the magic of your first Nintendo.**

Remember the jump you kept missing? You knew exactly where to press A. Then one afternoon you finally landed it, and the first thing you said was, “Did you see that?”

You can give your kid a little of that feeling. Let them take another run at a level, draw a monster with the stylus, or record the voice they think it would have. The best part might be when they hand you the 2DS and say, “Here. You try.”

*Less scrolling. More imagination.*

Level 1-1 is a setup project for parents with an original Nintendo 2DS. The idea is to pick a few games and creative tools for your kid to explore. The curated experiences are meant to work with Wi-Fi off, free of ads and in-app purchases. An adult may need internet access for setup.

**Project status:** Early planning. The tested app list, themes, and AI setup assistant are proposed.

## What kids can do

| Activity | What goes on the 2DS |
| --- | --- |
| Beat a level | Start with a few compatible Nintendo DS or 3DS games the family owns. |
| Take photos and make short videos | Use the built-in Nintendo 3DS Camera. |
| Record a voice or sound effect | Use the built-in Nintendo 3DS Sound app. |
| Make a Mii | Use the built-in Mii Maker. |
| Draw with the stylus | Try Magic Draw as a homebrew candidate. [Upstream project](https://github.com/natsuneco/magic-draw) |
| Make a frame-by-frame cartoon | Try 3DS Motion as a homebrew candidate. [Upstream project](https://github.com/norips/3DS_Motion) |

The camera, sound recorder, and Mii Maker are a starting point on a stock system. [Nintendo 2DS operations manual](https://csassets.nintendo.com/noaext/image/private/t_KA_PDF/manual-nintendo-2ds-operations-english)

Parents choose what goes on the handheld and how photos and recordings are shared. For each homebrew candidate, the project will check the upstream source and license, then test launch, offline use, and saving and reopening a creation on the original 2DS. Optional themes can personalize the HOME Menu when the console and region support them.

## Version 1 scope

Version 1 targets the original, wedge-shaped Nintendo 2DS. The New Nintendo 2DS XL and other 3DS-family models are outside the first release’s test scope.

The first release should be a short parent checklist and a small list of tested apps with upstream links. Keep setup manual and easy to follow. Add automation only where testing shows it removes a recurring setup problem. That’s the Ponytail approach for this project.

## Bring your own games

Use compatible cartridges you own or digital games you lawfully acquired and can access on your system. Use personal backups only where permitted. Level 1-1 will link to authorized homebrew releases and will exclude commercial ROMs, game downloads, BIOS files, title keys, and piracy sources.

## Gear for a secondhand 2DS

- **A padded zip case.** Look for a case sized for the original wedge-shaped 2DS. A soft divider keeps cartridges and the charging adapter away from the exposed screens.
- **Screen protectors for both screens.** Get an original 2DS set with a lower protector designed for stylus input. Test the touch screen from corner to corner after applying it. [Nintendo 2DS operations manual](https://csassets.nintendo.com/noaext/image/private/t_KA_PDF/manual-nintendo-2ds-operations-english)
- **A USB-C charging adapter.** For travel, look for an external adapter that explicitly supports the original 2DS and use the power supply specified by its maker. Keep the Nintendo wall charger as your baseline for testing a used handheld. [Hyperkin charging kit](https://wholesale.hyperkin.com/products/shockline-type-c-usb-power-supply-for-3ds-2ds-dsi-10w-5v) · [Nintendo AC adapter](https://www.nintendo.com/us/store/products/ac-adapter-nintendo-2ds-nintendo-3ds-xl-nintendo-3ds-nintendo-dsi-xl-and-nintendo-dsi-82577/)
- **A spare stylus and room for a few cartridges.** Choose a stylus that fits the original 2DS slot. A few cartridge sleeves in the case make it easy for kids to find their favorites.
- **A replacement Circle Pad if the used one needs it.** Test the stick in all directions and check that it returns to center. If the cap is worn or missing, look for an original 2DS-compatible cap. If movement drifts, try the system’s Circle Pad calibration first. Persistent drift or dead directions can point to the joystick module. Verify the part against your model before opening the shell, or have a repair shop handle it. [iFixit original 2DS repair reference](https://www.ifixit.com/Device/Nintendo_2DS)

Check the charging port, battery life, shoulder buttons, sleep switch, and cartridge slot while you’re still in the seller’s return window. Test a game and draw a few lines on the touch screen before buying repair parts.

## Before setup

- Have a working original Nintendo 2DS, stylus, compatible charger, reliable SD card, and a computer with an SD card reader and internet access.
- Try the stock camera, sound recorder, Mii Maker, and any cartridges first. Back up existing SD card contents and any photos, recordings, or saves you want to keep before changing files.
- For optional homebrew, have an adult confirm the console model, system version and region, and whether custom firmware is already installed. Follow the current guide for that console. Keep the system charged, preserve the recovery backups the guide creates, and stop if a screen or error differs from the documented step. [3DS Hacks Guide](https://3ds.hacks.guide/)
- Before handing it over, turn off Wi-Fi, review parental controls and browser access, and launch every selected game and app. Save and reopen a test creation. Keep setup tools out of the child’s usual play area.

## Planned setup assistant

Taking a cue from [WiiReady](https://github.com/jcb79107/wiiready), the planned AI assistant would guide an adult one verified step at a time. It would confirm the model, region, system version, and existing firmware state, then point to the matching section of the live 3DS Hacks Guide. The adult would perform each step and confirm what appears on screen. If the state is unclear or a step fails, the assistant would pause and point to the guide’s troubleshooting. Filesystem changes and firmware installation stay in the adult’s hands. Everyday play requires no AI assistant.

## Phased plan

1. **Write and test the stock setup.** Use an original 2DS to verify the built-in creative activities, cartridge play, and parent handoff with Wi-Fi off.
2. **Pilot a small homebrew selection.** Test a drawing tool and an animation tool on original hardware. Document tested versions, save behavior, upstream links, and recovery steps. Try an optional theme on a compatible console.
3. **Prototype guided setup.** Use the tested checklist to try the WiiReady-inspired walkthrough with parents. Check that they can identify the device state, follow the right guide branch, and recover from common setup mistakes.
4. **Publish v1 after a parent pilot.** Confirm that parents can repeat the setup and that kids can open the selected games and tools and find their saved creations offline.

Level 1-1 is an independent project. Nintendo, Nintendo 2DS, and Mii are Nintendo marks.
