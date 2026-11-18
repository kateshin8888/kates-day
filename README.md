# Kate's Day

_You make your day._

A cozy 3D to-do game. Your character lives in a little house, walks to the room where each real-life quest happens, and earns XP to level up and buy upgrades.

## Play it

Open `index.html` in a browser, or turn on GitHub Pages for this repository (Settings → Pages → Deploy from branch → `main` / root) and open the link it gives you.

## Focus time

While the page is open, you earn 1 XP every minute, plus 5 bonus XP for every 25 minutes of focus in a day. It keeps counting when you switch to other tabs, sites or apps, like a study timer. It stops when you close the tab, and time while your computer is asleep is not counted.

## Study groups (multiplayer)

Open the **Group** tab to make a study group or join one with a 5-letter code. Everyone in a group shares one house: you see each other's heroes walking between the rooms, what room each person is in, and how long everyone has focused today. Tap your hero to wave, or tap a friend's hero to see what they're up to.

Your quests and planner stay private. Friends only see your hero, name, level, which room you're in, and your focus time today.

Multiplayer runs on Claude's built-in live rooms, so it works when the game is opened from its Claude link while signed in to Claude. There's no server or account to set up. To play with friends, share the game from the Share menu (invite them by email), then send them your group code. Opened as a plain file or from GitHub Pages, the game still works, just solo.

## Notes

- Everything is in one file, `index.html`. It loads three.js r128 from cdnjs and fonts from Google Fonts.
- Progress is saved in your browser (localStorage), so it stays on the device and browser you play on.
