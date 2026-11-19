# Kate's Day

_You make your day._

A cozy 3D to-do game. Your character lives in a little house, walks to the room where each real-life quest happens, and earns XP to level up and buy upgrades.

## Play it

Open `index.html` in a browser, or turn on GitHub Pages for this repository (Settings → Pages → Deploy from branch → `main` / root) and open the link it gives you.

## Focus time

While the page is open, you earn 1 XP every minute, plus 5 bonus XP for every 25 minutes of focus in a day. It keeps counting when you switch to other tabs, sites or apps, like a study timer. It stops when you close the tab, and time while your computer is asleep is not counted.

## Study groups (multiplayer)

Everyone who has the game open shares one main house, so you see other players' heroes walking around as soon as you arrive. The **Group** tab lists who's in the house. For a quieter house just for friends, make a study group or join one with a 5-letter code. Everyone in a group shares their own house: you see each other's heroes walking between the rooms, what room each person is in, and how long everyone has focused today. Tap your hero to wave, or tap a friend's hero to see what they're up to.

Your quests and planner stay private. Friends only see your hero, name, level, which room you're in, and your focus time today.

Multiplayer works in two places, with no server or account to set up:

- **The website (GitHub Pages):** players connect to each other directly (peer to peer) using [Trystero](https://github.com/dmotz/trystero), which finds other players through free public Nostr relays. Just share the website link.
- **The Claude link:** uses Claude's built-in live rooms. Share the game from the Share menu (invite friends by email).

Players on the website and players on the Claude link are in separate houses, so pick one place for your friends to play. Opened as a plain file on your computer, the game works solo. On some strict school or office networks, direct connections can be blocked, and the game then plays solo there.

## Notes

- The game is one file, `index.html`. It loads three.js r128 from cdnjs and fonts from Google Fonts. `trystero.min.js` is a bundled copy of Trystero 0.26.0 (MIT license), loaded only on the website.
- Progress is saved in your browser (localStorage), so it stays on the device and browser you play on.
