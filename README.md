<div align="center">

# GroupBulletinBoard

![Version](https://img.shields.io/badge/version-v1.6.0-blue.svg)
![License](https://img.shields.io/github/license/Xurkon/GroupBulletinBoard?style=for-the-badge&label=LICENSE&color=2980b9)
![Game](https://img.shields.io/badge/GAME-WOW_3.3.5a-blue?style=for-the-badge&logo=battle.net&logoColor=white)
![Platform](https://img.shields.io/badge/PLATFORM-PROJECT_ASCENSION-orange?style=for-the-badge)
![Downloads](https://img.shields.io/github/downloads/Xurkon/GroupBulletinBoard/total?style=for-the-badge&label=DOWNLOADS&color=e67e22)

<br/>

**LFG/LFM Request Aggregator for World of Warcraft 3.3.5a**

[⬇ **Download Latest**](https://github.com/Xurkon/GroupBulletinBoard/releases/latest) &nbsp;&nbsp;•&nbsp;&nbsp; [📂 **View Source**](https://github.com/Xurkon/GroupBulletinBoard)

</div>

---

## ✨ Features

### 🔍 Smart Request Detection

Detects all LFG/LFM requests from chat channels, sorts them by dungeon, and presents them in a clean organized list.

### 🎮 Ascension Support

Dedicated **Ascension Filter** for custom dungeons like **Vault of the Inquisition** and **Road to De' Other Side**.

### 🌍 Multi-Language Support

Natively recognizes dungeons in **English**, **German**, **Russian**, **French**, and **Chinese**. Easily customizable for any language.

### 🔔 Notifications

Get notified about new requests via **sound** or **chat notifications** - never miss a group again!

### ⚡ Performance Optimized

UI throttling and caching ensure smooth performance even during heavy trade channel spam.

### 🎨 Customizable Filters

Filter by dungeon, level range, heroic/normal mode, and more. Fold/unfold dungeons to focus on what you need.

---

## 📥 Installation

1. Download the latest release from the link above
2. Extract to `Interface/AddOns/GroupBulletinBoard`
3. Restart WoW or `/reload` if in-game
4. Click the minimap button or type `/gbb` to open

---

## 🔧 Usage

### Opening the Addon

- Click the **minimap button**
- Or type `/gbb` in chat

### Interacting with Requests

- **Left-click**: Whisper the player
- **Shift + Left-click**: `/who` the player
- **Ctrl + Left-click**: Invite the player
- **Click dungeon name**: Fold/unfold that dungeon

### Slash Commands

| Command | Description |
|---------|-------------|
| `/gbb` | Open main window |
| `/gbb config` | Open settings |
| `/gbb reset` | Reset window position |
| `/gbb notify chat <on/off>` | Toggle chat notifications |
| `/gbb notify sound <on/off>` | Toggle sound notifications |
| `/gbb help` | Show all commands |

---

## ⚙️ Settings

Access settings via **Interface → AddOns → Group Bulletin...** or `/gbb config`

### Filter Panels

- **Vanilla Filter**: Classic dungeons (RFC through Naxx)
- **TBC Filter**: Burning Crusade dungeons
- **WotLK Filter**: Wrath of the Lich King dungeons
- **Ascension Filter**: Custom Ascension dungeons (VOTI, RDOS)

### Search Patterns

Customize which keywords trigger dungeon detection. Add your own patterns or blacklist words.

---

## 📜 Changelog

See [changelog.md](changelog.md) for full version history.

### v1.6.0 - Ascension Update

- **Ascension Filter**: New panel for Vault of the Inquisition & Road to De' Other Side
- **Fixed**: Message position jumping bug
- **Optimized**: UI throttling and caching for better performance

---

## 👥 Credits

- **Xurkon** - Ascension port & optimizations
- **fondlez** - WotLK 3.3.5a port
- **Obszczymucha (Ohhaimark)** - TBC 2.4.3 backport
- **Vyscî-Whitemane** - Classic TBC addon
- **GPI / Erytheia-Razorfen** - Original addon

---

## 📄 License

See [LICENSE](LICENSE) for details.
