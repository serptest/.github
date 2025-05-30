# 🎮 SerpTest Games

Welcome to SerpTest Games - Play browser games instantly, no downloads required!

## 🕹️ Play Now

Visit our games hub: **[serptest.github.io](https://serptest.github.io/)**

## 🎯 Available Games

### [🐍 Snake Game](https://serptest.github.io/play/snake)
Classic snake game - eat food and grow longer! Use arrow keys to control.
- Repository: [serptest/snake-game](https://github.com/serptest/snake-game)
- Install: `npm install github:serptest/snake-game`

### More games coming soon!

## 🏗️ Architecture

Our platform uses a unique architecture where:
- Each game is a standalone NPM package
- Games are dynamically loaded on-demand
- No rebuilding needed when adding new games
- Every game has its own repository

## 🤝 Contributing

Want to add your own game? It's easy!

1. Create a game following our [game template](https://github.com/serptest/snake-game)
2. Your game must export a class with `constructor(container)`, `start()`, and `stop()` methods
3. Submit a PR to add it to our catalog

## 🔧 For Developers

### Use our games in your project:

```bash
npm install github:serptest/snake-game
```

```javascript
import SnakeGame from '@serptest/snake-game'

const game = new SnakeGame(container)
game.start()
```

## 📚 Resources

- [Main Site Repository](https://github.com/serptest/serptest.github.io)
- [Architecture Documentation](https://github.com/serptest/serptest.github.io/blob/main/ARCHITECTURE.md)
- [Game Template](https://github.com/serptest/snake-game)

---

*Built with ❤️ using Nuxt 3 and GitHub Pages*