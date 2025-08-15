# 🎨 ConicEmojis

**ConicEmojis** is a lightweight Minecraft plugin that lets you use **custom emojis and text replacements** in chat with full **tab completion** support.  
Simply type `:EmojiName:` in chat, and it will be replaced with your configured symbol or text.

📥 **Download:** [Modrinth](https://modrinth.com/plugin/conicemojis)  
💬 **Community:** [Discord](https://discord.gg/JvVv7wHQc7)

---

## 📸 Plugin Preview
![ConicEmojis In-Game](https://i.postimg.cc/MKSqZ43s/2025-08-15-15-52-05.png)

---

## ✨ Features
- ✅ Custom emojis & text replacements
- ✅ Tab completion for all configured emojis
- ✅ Easy configuration via `config.yml`
- ✅ RGB color support (requires chat formatter)
- ✅ Lightweight & fast performance

---

## ⚙️ Configuration
``config.yml``
```
# ==================================== #
#            CONIC EMOJIS              #
#         V-1.0.0 - Configuration      #
# ==================================== #
# Add as many as you want. The symbol must be valid in-game.
# USE :EmojiName: to use the symbol in chat.
emojis:
  skull: '&c☠'
  heart: '&#FF0000❤' # RGB only works with chat formatters like LPC or EssentialsX Chat
  testtext: '&cThis is test text.'
```

---

## 📦 Commands & Permissions

### Commands
| Command | Description |
|---------|-------------|
| `/conicemoji reload` | Reloads the configuration |
| `/conicemoji list`   | Lists all available emojis |

### Permissions
| Permission | Description | Default |
|------------|-------------|---------|
| `conicemoji.use`   | Allows use of emoji commands | OP |
| `conicemoji.reload`| Allows reloading the plugin   | OP |
| `conicemoji.list`  | Allows viewing the emoji list | true |

---

## 📜 Usage
1. Install the plugin on your Spigot/Paper server (1.21+)
2. Edit `config.yml` to add your custom emojis
3. Use `:EmojiName:` in chat
4. Enjoy your custom emojis 🎉

---

## 📌 Links
- [📥 Download from Modrinth](https://modrinth.com/plugin/conicemojis)  
- [💬 Join our Discord](https://discord.gg/JvVv7wHQc7)  
