# 🐤 Flappy Bird in Desmos
A Flappy Bird clone made in the [Desmos Graphing Calculator](https://www.desmos.com/calculator)

## 🕹️ Try it out
### 📘 From this repository
1. Go to this repository's [web page](https://kanagrou.github.io/flappy-bird/)
2. Have fun!

### 📗 From Desmos
1. Open [Desmos](https://www.desmos.com/calculator)
2. Open **inspect element** ( `Ctrl`+`Shift`+`I` ) or ( `⌘`+`⌥`+`I` )
3. Type this command:
```js
fetch('https://raw.githubusercontent.com/kanagrou/flappy-bird/main/src/calc.json')
    .then(res => res.json())
    .then(state => Calc.setState(state))
```
4. Have fun!

## 📷 Screenshots

## Start Screen
![Start Screen](screenshots/startscreen.png)
## In game
![In game](screenshots/ingame.png)
## Game over
![Gameover](screenshots/gameover.png)
