# Eat Me!

Two hungry bubbles in animal costumes, one picnic table. Snack your way bigger, then gobble your rival.

A pixel-art browser game that runs on desktop and phone. No install, no sign-up: open `index.html` or the GitHub Pages link.

## How to play

- Eat food to grow. Fruit is a nibble, ice cream and snacks fill you up, fries and fried chicken make you huge.
- The % over each bubble is its size compared with its rival.
  - **115% or more** (green, EAT!): you can eat your rival. Reach their middle to take the bite.
  - **Under 87%** (red, RUN!): your rival can eat you.
- A round ends when someone gets eaten. After 60 seconds, the bigger bubble takes the round.
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
