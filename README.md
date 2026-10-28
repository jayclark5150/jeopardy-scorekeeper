# Jeopardy Scorekeeper

A phone-friendly score tracker for playing along while you watch Jeopardy on TV.

- Right column adds clue values, Wrong column subtracts them
- Toggle between Jeopardy! ($200 to $1,000) and Double Jeopardy! ($400 to $2,000)
- Daily Double wager with a Max button (your score or the top clue, whichever is higher)
- Final Jeopardy wager (up to your full score, or $0 to sit it out)
- Undo last, recent clue list, and a two-tap New game reset
- Score is saved in the browser, so it survives closing the tab

## Use it

It is a single static file with no build step. Open `index.html` in a browser, or host the repo with GitHub Pages and open the link on your phone.

The score is stored in each browser's local storage, so a phone and a laptop keep separate scores.
