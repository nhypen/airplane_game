# ✈️ Airplane Game

A simple arcade-style browser game built with pure HTML, CSS, and JavaScript.

Control your airplane, destroy enemy aircraft, collect power-ups, survive boss battles, and achieve the highest score possible.

## 🎮 Features

- Smooth airplane movement
- Move left, right, up, and down
- Rainbow bullets
- Click or hold Space to shoot
- Double Shot power-up
- Pixel-style healing hearts
- Dynamic difficulty scaling
- Boss battles every 200 points
- Stronger bosses at higher scores
- Boss projectiles
- Particle explosion effects
- Sound effects
- Background music
- High score saved in Local Storage
- Game Over screen with restart option

## 🕹 Controls

| Key | Action |
|-------|----------|
| A / Left Arrow | Move Left |
| D / Right Arrow | Move Right |
| W / Up Arrow | Move Up |
| S / Down Arrow | Move Down |
| Space | Shoot / Auto Fire |
| R | Restart Game |

## 👾 Enemies

Enemy aircraft continuously appear and become faster as the game progresses.

Destroying enemies increases your score.

## 💚 Hearts

Pixel hearts occasionally fall from the sky.

Collect them to restore health.

Maximum lives: **10**

## 🌈 Double Shot Power-Up

Collect the **2X** power-up to activate Double Shot mode.

While active, your airplane fires two bullets at once.

## 👑 Boss Battles

A boss appears every **200 points**:

- 200 points → Boss #1
- 400 points → Boss #2
- 600 points → Boss #3
- and so on...

Each new boss:
- Has more HP
- Moves faster
- Becomes more challenging

Defeating a boss rewards bonus points and unlocks the next boss stage.

## 🏆 High Score

The game automatically saves your best score using:

```javascript
localStorage
```

Your record remains saved even after refreshing the page.

PLAY DIRECTLY IN YOUR BROWSER. No installation required.

(https://nhypen.github.io/airplane_game/)

## 🛠 Technologies

- HTML5
- CSS3
- JavaScript
- Canvas API
- Web Audio API
- Local Storage

## 🎯 Future Ideas

- Multiple airplane skins
- Achievement system
- Animated start screen
- Meteor enemies
- Lightning special attack
- Boss attack patterns
- Shop and upgrades
- Mobile support

---
## Author
nhypen
