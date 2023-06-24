# Yeat's Bloxflip Predictor

Bloxflip Predictor written in Batch using customtkinter and hiddenselenium

https://discord.gg/daddyderek

Very high accuracy (>85%) in mines, crash, etc. 

**HOW TO USE:**
1. Run predictor.exe from releases (https://github.com/crymsons/yeats-bloxflip-predictor/releases/tag/V1.1.4)

2. Wait for the prompt that says "Looking for Bloxflip instance" and then open the Bloxflip website. The predictor will automatically find your browser window and launch the GUI.

3. Select game mode in the predictor and run the same mode on the Bloxflip website.

4. Enjoy! 

- **NOTE:** DO *NOT* WIN OVER 10K ROBUX IN THE SAME DAY USING THIS. Bloxflip staff will check your win logs and catch on because of the high win rate / accuracy.

Q: What browsers are supported?

A: Currently, most modern browsers that are compatible with selenium such as Chrome, Brave, OperaGX, Edge, and Firefox are supported. Safari may work too, but it has not been tested as it uses MacOS.


Q: Crashed with error code 400 : Invalid Website.

A: This means it could not find an instance of bloxflip running in your browser. Try restarting your browser or using a different one. This will be fixed in a future update to be more reliable.

TODO:
- Use pypuppeteer or playwright instead of hiddenselenium which is outdated.
- Convert into a discord bot.
- Make predictions based on round ids instead of injecting into browser.
- Fix random crashes (MOSTLY DONE)
- Implement support for MacOS and Linux.
- Change color scheme based on system color settings. (DONE)
