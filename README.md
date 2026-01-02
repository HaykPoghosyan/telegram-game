# Telegram Tic Tac Toe HTML5 Game

A real-time multiplayer Tic Tac Toe HTML5 game for Telegram built with Node.js, Telegraf, Express, and Socket.io.

## ✨ Features

- **Real HTML5 Game**: Full game interface in browser
- **Real-time Multiplayer**: Instant move updates via WebSockets
- **Beautiful UI**: Modern gradient design with animations
- **Telegram Integration**: Works natively in Telegram
- **Share to Play**: Easy multiplayer via Telegram's share feature

## 🚀 Quick Start

**📖 Read `START_GAME.txt` for complete setup instructions!**

### Quick Steps:

1. **Start tunnel**:
   ```bash
   npm run tunnel
   ```

2. **Configure @BotFather** (one-time):
   - `/setinline` → Enable inline mode
   - `/editgame` → Set game URL

3. **Update `config.js`** with your tunnel URL

4. **Start bot**:
   ```bash
   npm start
   ```

5. **Test**: Open Telegram → `@space_arcade_bot` → `/play`

## 🎮 How to Play

1. Open Telegram → `@space_arcade_bot`
2. Send `/play`
3. Game opens in browser!
4. Share game with a friend → Both play in real-time
5. First to get 3 in a row wins!

## 📁 Project Structure

- `bot.js` - Main bot with game handlers
- `gameServer.js` - Express + Socket.io server
- `gameLogic.js` - Tic Tac Toe game rules
- `public/game.html` - HTML5 game interface
- `config.js` - Bot configuration
- `START_GAME.txt` - Setup instructions

## 📝 Notes

- LocalTunnel URL changes on each restart
- Games auto-cleanup after 5 minutes
- For production, use Heroku/Railway/Vercel
- Keep tunnel and bot running simultaneously

# telegram-game
# telegram-game
