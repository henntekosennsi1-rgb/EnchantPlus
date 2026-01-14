# EnchantPlus

[![Version](https://img.shields.io/badge/version-2.0.0-green.svg)]()
[![Minecraft](https://img.shields.io/badge/Minecraft-1.21-blue.svg)]()
[![Bedrock](https://img.shields.io/badge/Bedrock-Compatible-orange.svg)]()

19 powerful custom enchantments with portable anvil GUI system

## ⚔️ Features

- **19 Custom Enchantments** - Movement, Combat, and Utility types
- **Portable Anvil GUI** - Right-click anvils for custom interface
- **Villager Trading** - Custom enchant merchants
- **Bedrock Support** - 13/19 enchantments work with Geyser
- **Permission System** - Granular control over features
- **Highly Configurable** - Adjust all values and limits

## 📦 Enchantments

### Movement & Mobility (6)
- Movement Speed, Jump Boost, Step Height
- Slow Falling, Knockback Resistance, Block Range

### Combat & Defense (5)
- Fire Resistance, Regeneration, Absorption
- Armor Toughness, Thorns

### Utility & Support (8)
- XP Multiplier, Mining Speed, Luck, Item Repair
- Water Breathing, Night Vision, Invisibility, Saturation

## 🚀 Installation

1. Download EnchantPlus.jar
2. Place in `/plugins/` folder
3. Restart server
4. Configure permissions
5. Start using!

## 📋 Commands

- `/enchantplus` - Open portable anvil
- `/enchant list` - List all enchantments
- `/enchant give <enchant> <level>` - Give enchanted book
- `/enchantvillager` - Spawn merchant

## ⚙️ Configuration
```yaml
portable-anvil:
  enabled: true
enchantments:
  movement_speed:
    max_level: 25
    bedrock_compatible: true
```

## 🔑 Permissions

- `enchantplus.player` - Player permissions
- `enchantplus.moderator` - Mod permissions
- `enchantplus.admin` - Admin permissions

## 📦 Requirements

- Paper/Spigot 1.21+
- Java 21+
- Optional: Geyser for Bedrock

## 💬 Support

Discord: https://discord.gg/zYY55dzhjd

---
Made with ❤️ by henrry for MattariMinecraft
