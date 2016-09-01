# GamerBot-Game-Destiny

A Destiny module for GamerBots

See [`src/GamerBot-Game-Destiny.coffee`](src/GamerBot-Game-Destiny.coffee) for full documentation.

## Installation

In hubot project repo, run:

`npm install git+https://git@github.com/GamerBot/GamerBot-Game-Destiny --save`

Then add **GamerBot-Game-Destiny** to your `external-scripts.json`:

```json
[
  "GamerBot-Game-Destiny"
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
