# Tarot API

A free image API for the Rider-Waite tarot deck. 78 cards, public domain.

Made as part of a React hooks tutorial series on TikTok and YouTube by [petaloverflow](https://github.com/petaloverflow).

## Endpoints

```
/cards.json       all 78 cards
/major.json       22 Major Arcana
/minor.json       56 Minor Arcana
/wands.json       Suit of Wands
/cups.json        Suit of Cups
/swords.json      Suit of Swords
/pentacles.json   Suit of Pentacles
```

## Each card

```json
{ "name": "The Fool", "image": "https://petaloverflow.github.io/tarot-api/cards/ar00.jpg" }
```

## Usage

```js
fetch("https://petaloverflow.github.io/tarot-api/major.json")
  .then(res => res.json())
  .then(cards => console.log(cards))
```

## Images

Card images are from the Rider-Waite deck (1909) and are in the public domain.
