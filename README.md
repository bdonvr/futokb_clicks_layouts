# futokb_clicks_layouts
Custom layouts for the Android keyboard FUTO that mimick the physical keyboard of the Clicks Communicator

Inspired by work done by [@Daatewulike](https://github.com/kaiserkueche) here: https://github.com/kaiserkueche/Daatewulike/tree/main/futo%20keyboard

Additional layouts wanted. Feel free to make a pull request.

Currently done:
- English QWERTY

Needed:
- French AZERTY
- German QWERTZ
- Korean
- Arabic

Preview (NOTE: There was an issue with the % symbol not appearing above the V key, this has been fixed)

<img width="386" height="306" alt="Screenshot_20260919_023120_Gallery" src="https://github.com/user-attachments/assets/22287a02-5f23-41a1-b435-4c04d80ea821" /> <img width="386" height="309" alt="Screenshot_20260919_023130_Gallery" src="https://github.com/user-attachments/assets/e7259b2f-55ac-4357-b804-55d5dacb7030" />

<img width="368" height="670" alt="typing" src="https://github.com/user-attachments/assets/62b07f14-499d-4a3a-95d1-debe283db951" /> 

---
CAVEATS:

1. Ctrl, alt, search, and Clicks keys don't exist/work
2. FUTO, AFAIK does not support making the shift and symbol keys something that only works when held. It functions like the typical sticky software key. But you can still hold it down and as long as you type one symbol/letter, it will return to the main layout when you let go. So for maximum realism you need to make sure to hold it and to type something whenever you do.
3. You can long press a key for symbols, but from what I know this won't work on Clicks. I set them up that way just to have them both shown like on the real keyboard. You're meant to hold down the symbol key.
4. The 0 key is paired with CTRL on the real Communicator, which is not something FUBO supports. Here it is a space character paired with 0. I tried to make the key do nothing but it does not seem to be possible.
---

How to enable:

1. [Download and enable the FUTO Keyboard](https://keyboard.futo.tech/#download) (Available on Google Play, their F-Droid Repo, or as an .apk right from GitHub)
2. Open the "FUTO Keyboard" app.
3. Scroll down and click on "Help & Feedback"
4. Tap the line that says "Version Code: #####" 10 times until it says you're a developer
5. Back out and go into developer settings and select "Custom Layouts"
6. Tap "Create a new layout"
7. Set the "Language" to whatever language you're using so that autocorrect and such work, if desired.
8. Clear out the default example code.
9. Paste the desired layout from the text file found in the folders in this repository (for example, standard US QWERTY is in [EN_US/QWERTY.txt](https://github.com/bdonvr/futokb_clicks_layouts/blob/main/EN_US/QWERTY.txt). You can test it, but it will crash if you hit the symbols button until you complete step 10.
10. Save, then repeat steps 6 through 9, but instead pasting the SYMBOLS.txt file from the same folder that you got your layout from.
11. Go back to the main settings menu and select "Keyboard and Typing", then "Long-Press Keys & Spacebar"
12. Enable "Show Hints"

NOTE: If you follow these instructions your chosen layout should be "Custom Layout 0" and the symbols should be "Custom Layout 1". If you for some reason have other custom layouts you may need to edit the line that says "symbols: "custom1"" in the layout to point to the correct symbols layout. The keyboard will crash if you hit the symbol key and the referenced layout does not exist. (for example after you added the main layout but before you add the symbols layout.
