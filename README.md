# Eat Me!

Two hungry bubbles in animal costumes, one picnic table. Snack your way bigger, then gobble your rival.

A pixel-art browser game for desktop and phone, simple enough for little kids. No install, no sign-up: open `index.html` or the GitHub Pages link.

## How to play

- Everyone starts at size **1**. Food makes your number go up: fruit **+1**, ice cream and snacks **+2**, fries **+3**, fried chicken **+4**.
- **Bigger number eats smaller number!**
  - Green tag (EAT!): your number is bigger, so go get them. Reach their middle to take the bite.
  - Red tag (RUN!): their number is bigger, so run away.
  - Same number: you just bounce off each other.
- Bigger bubbles are a little slower, so the smaller one can get away.
- A round ends when someone gets eaten. After 60 seconds, the bigger number wins the round. Win 2 of 3 rounds to win the match.

## Things on the table

| | What it does |
|---|---|
| Snacks | Make you bigger. Both sides of the table start with the same snacks, and new ones drop on whichever side has fewer. |
| Shoe | Don't touch! It stomps you flat and you can't move for 3 seconds. Up to 3 shoes at a time, and they hop to new spots. |
| Blinking star | Grab it to zoom fast for 4 seconds. |
| Magic potion | Drink it to freeze your rival in ice for 3 seconds. |

The star and the potion appear now and then in the middle of the table, so both players can race for them. A frozen bubble can still be eaten!

## Controls

| | Player 1 | Player 2 |
|---|---|---|
| Keyboard | W A S D | Arrow keys |
| Phone / tablet | Drag on the left (or top) half | Drag on the right (or bottom) half |

Against the computer, either set of keys works, and you can drag anywhere on the screen.

## Modes

- **Vs computer**: Easy, Normal or Hard
- **2 players, one device**: share a keyboard or a tablet
- **Play a friend online**: tap *Create a game* and send your friend the invite link (or the 4-letter code). They join from any browser on any device, no sign-in needed. Keep the page open while you play. Some school or office Wi-Fi blocks peer-to-peer games; mobile data usually works.

## Costumes

Bear with a green cap, dinosaur with a blue cap, orca with a little red bow, orange tiger, and grey elephant. Pick yours on the menu.

## Credits

- Colours: the PixelHans palette.
- Online play: [PeerJS](https://peerjs.com/) (MIT licence), bundled in the page, using its free public connection server.
- Fonts: Press Start 2P and Pixelify Sans from Google Fonts.

## Tech

One self-contained HTML file: canvas pixel art drawn in code, synthesized Web Audio sound effects, and no build step.
