# Teen Patti Table

Teen Patti for family and friends, played with pretend coins. No sign-up needed.

## How to play

- **Host a room**: one person opens the page, taps *Host a room* and shares the room code or invite link.
  The host's device runs the table, so it must stay open during the game.
- **Join a room**: everyone else opens the link (or enters the code) on their own phone or laptop.
- **Pass and play**: one device passed around. Works offline.

Devices connect to each other directly (WebRTC via [PeerJS](https://peerjs.com)), using PeerJS's free public server only to find each other.
Each player only receives their own cards from the host. The host's browser holds the full deck, so it's built for friendly games, not for real money.

It's a single `index.html` with no build step.
