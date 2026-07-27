JOSEPHINE'S KITCHEN — VERSION 5.0

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

DATA
The app saves the current week, pantry checks, homemade-staple status, grocery checks, manual additions, and remembered items in Safari local storage on that iPhone. Remembering an item updates local app data; a static website cannot rewrite pantry.json on the server.

NUTRITION
Calories, protein, and fiber are rough per-serving ranges, not calculated nutrition facts.
