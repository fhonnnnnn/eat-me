# Eat Me!

Two hungry bubbles in animal costumes, one picnic table. Snack your way bigger, then gobble your rival.

A pixel-art browser game that runs on desktop and phone. No install, no sign-up: open `index.html` or the GitHub Pages link.

## How to play

- Everyone starts at size **1**. Food makes your number go up: fruit **+1**, ice cream and snacks **+2**, fries **+3**, fried chicken **+4**.
- **Bigger number eats smaller number!**
  - Green tag (EAT!): your number is bigger, so go get them. Reach their middle to take the bite.
  - Red tag (RUN!): their number is bigger, so run away.
  - Same number: you just bounce off each other.
- Bigger bubbles are a little slower, so the smaller one can get away.
- A round ends when someone gets eaten. After 60 seconds, the bigger number wins the round.
- Win 2 of 3 rounds to win the match.

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

Cow, shark, pig, fox, penguin and raccoon. Pick yours on the menu.

## Tech

One self-contained HTML file: canvas pixel art, synthesized Web Audio sound effects, and no build step. Online play is peer-to-peer through [PeerJS](https://peerjs.com/) (MIT licence, bundled in the page) and its free public connection server. The only other outside files are two Google Fonts.
