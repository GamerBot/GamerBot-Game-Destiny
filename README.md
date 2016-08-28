# GamerBot-Game-Destiny

A Destiny module for GamerBots

See [`src/gamerbot-game-destiny.coffee`](src/gamerbot-game-destiny.coffee) for full documentation.

## Installation

In hubot project repo, run:

`npm install git+https://git@github.com/ssoriche/GamerBot-Game-Destiny --save`

Then add **gamerbot-game-destiny** to your `external-scripts.json`:

```json
[
  "gamerbot-game-destiny"
]
```

## Sample Interaction

```
user1>> .dtg
hubot>> Destiny
user1>> .dtg events
hubot>> Events:
        CoE ... Challenge of Elder's
        KFHM ... King's Fall Hard Mode
```

[![Build Status](https://travis-ci.org/GamerBot/GamerBot-Game-Destiny.svg?branch=master)](https://travis-ci.org/GamerBot/GamerBot-Game-Destiny)
