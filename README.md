# Minecraft Skript Generator

A simple web-based tool to convert Minecraft summon commands into Skript plugin format.

## 🔗 Live Demo

**[https://git.hsinghhira.me/MinecraftSkriptGenerator/](https://git.hsinghhira.me/MinecraftSkriptGenerator/)**

## 📖 What is this?

This tool helps Minecraft server owners convert long, complex summon commands into easy-to-use Skript commands. Instead of running multiple commands manually, you can create a single custom command that spawns all your items at once.

## ✨ Features

- 🎯 **Simple Interface** - Just paste your commands and generate
- 🔄 **Automatic Conversion** - Converts Minecraft commands to Skript format
- 💾 **Download .sk Files** - Save your generated Skript directly
- ⚡ **Fast & Easy** - No installation required, works in your browser
- 🎨 **Clean Design** - Modern, user-friendly interface

## 🚀 How to Use

1. Visit the [Skript Generator](https://git.hsinghhira.me/MinecraftSkriptGenerator/)
2. Enter your desired command name (e.g., "yuva", "yoddha")
3. Paste your Minecraft summon commands in the textarea
4. Click **"Generate Skript"**
5. Click **"Save .sk File"** to download
6. Upload the .sk file to your server's `plugins/Skript/scripts/` folder
7. Run `/sk reload <filename>` on your server
8. Use your custom command in-game!

## 📝 Example

**Input:**
```
Command Name: warrior
Commands:
summon item ~ ~1 ~ {Item:{id:iron_helmet,...}}
summon item ~ ~1 ~ {Item:{id:iron_sword,...}}
```

**Output:**
A Skript file that creates the `/warrior` command, which spawns all items at your location.

## 🛠️ Requirements

- Minecraft Server (Spigot/Paper)
- [Skript Plugin](https://github.com/SkriptLang/Skript) installed on your server
- Permission: `<commandname>.give` (or be OP)

## 💡 Tips

- You can paste multiple summon commands at once
- Comments (lines starting with `//` or `#`) are automatically removed
- The tool converts double quotes to single quotes for Skript compatibility
- Generated commands spawn items at the player's location

## 🤝 Contributing

Found a bug or have a suggestion? Feel free to open an issue or submit a pull request!

## 📜 License

Free to use for personal and commercial Minecraft servers.

---

Made with ❤️ for the Minecraft community
