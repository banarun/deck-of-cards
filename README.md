# HTML5 Deck of Cards
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/pakastin/deck-of-cards?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

Pure vanilla JS (+ CSS3) – no dependencies.

http://pakastin.github.io/deck-of-cards

## Latest changes

- 0.0.3 big refactoring – code now easier to follow and in smaller pieces
- 0.0.2 made intro shorter & added "poker"
- 0.0.1 initial version


## Download

- [Production version (~5 KB uncompressed)](https://pakastin.github.io/deck-of-cards/dist/deck.min.js)
- [Development version (~15 KB uncompressed)](https://pakastin.github.io/deck-of-cards/dist/deck.js)


## Where's what?

[css/](https://github.com/pakastin/deck-of-cards/tree/master/css) - CSS source (stylus + nib) of the example

[dist/](https://github.com/pakastin/deck-of-cards/tree/master/dist) - deck.js & deck.min.js

[example/](https://github.com/pakastin/deck-of-cards/tree/master/example) - http://pakastin.github.io/deck-of-cards

[lib/](https://github.com/pakastin/deck-of-cards/tree/master/lib) - JS (ES6) source of dist/deck.js - deck.js is also the main file

[views/](https://github.com/pakastin/deck-of-cards/tree/master/views) - HTML source of the example


## Build instructions

    npm install
    npm start

(starts watching for changes..)

## Note to self: todo

- Make z-index temporary by reordering DOM elements between actions
- Enhance API, make more generic
- Make cards flippable
