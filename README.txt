JOSEPHINE'S KITCHEN — VERSION 5.1

FILES
- index.html: the complete app, with all meal data embedded so it works by itself.
- meals.json: editable reference copy of the meal and nutrition data.
- pantry.json: editable reference copy of pantry, kimchi, pickle, Fairlife, and remembered-item settings.
- manifest.json, sw.js, and icons: allow home-screen and offline behavior when hosted.
- APPLE_SHORTCUT_SETUP.txt: one-time instructions for sending the grocery list to Apple Reminders.

IPHONE USE
1. Upload this whole folder to any static website host.
2. Open index.html in Safari.
3. Tap Share.
4. Tap Add to Home Screen.

Important: iPhone Safari does not reliably run a full app directly from local files. Hosting the folder is the dependable way to get home-screen and offline behavior.

SHOPPING FEATURES
- Add one-off items with an optional quantity.
- Manual items persist until deleted or cleared.
- Tap Remember on a manual item to save it as a recurring pantry item.
- Copy exports a clean one-item-per-line list.
- Send to Reminders opens the iOS Share Sheet with the same clean list for an Apple Shortcut.
- Clear grocery list ends the current shopping session, removes one-off items, resets grocery checkmarks, and leaves meal plans, pantry data, and remembered items intact.
- After clearing, Start new list restores a fresh list from the current week and pantry; changing the week or pantry also starts a fresh list automatically.

DATA
The app saves the current week, pantry checks, homemade-staple status, grocery checks, manual additions, and remembered items in Safari local storage on that iPhone. Remembering an item updates local app data; a static website cannot rewrite pantry.json on the server.

NUTRITION
Calories, protein, and fiber are rough per-serving ranges, not calculated nutrition facts.

VERSION 5.2
- Adds occasional Summer rolls and Teriyaki salmon meals.
- Adds milk, relish, lemonade powder, Trader Joe's matcha latte mix, instant coffee, and hoisin sauce to pantry options.


Version 5.3 adds favorites, last-made tracking, recipe readiness, four weekly-plan generators (Favorites, Favorites + Surprise, Smallest Shop, Random), and the newly discussed meals and pantry items.


VERSION 5.4
- Adds butter to the Fridge pantry list.
- Removes duplicate Japanese mayonnaise, salsa, and BBQ sauce entries from Condiments; they remain under Fridge.
- Changes Bibimbap from “gochujang sauce” to “gochujang,” with an alias for older data.
- Adds milk to chocolate-chip banana bread/muffins and treats butter as required for crepes.
- Formats the embedded DATA section in index.html so recipe ingredients are easier to edit manually.

MANUALLY EDITING RECIPES
The live app uses the DATA block embedded near the top of index.html. Open index.html in a text editor, search for the recipe name, and edit that recipe’s ingredients object. The usual groups are required, chooseOne, chooseSeveral, and optional. Keep quotation marks, commas, square brackets, and braces valid.

meals.json is a readable reference copy, but changing meals.json alone does not currently change the live app. Make the same edit in meals.json if you want the reference file to stay synchronized.
