Fantasy-Female-Character-Generator/
│
├── README.md
├── LICENSE
├── prompts/
│   ├── armor.md
│   ├── clothing.md
│   ├── personalities.md
│   ├── weapons.md
│   └── styles.md
│
├── data/
│   ├── characters.json
│   ├── armors.json
│   ├── swords.json
│   └── outfits.json
│
├── examples/
│   ├── knight.md
│   ├── mage.md
│   ├── assassin.md
│   └── samurai.md
│
└── generator.py

{
  "name": "Alyssia",
  "age": 24,
  "race": "Elf",
  "height": "1.72m",
  "hair": {
    "color": "Silver",
    "style": "Long with braided ponytail"
  },
  "eyes": {
    "color": "Crimson",
    "effect": "Glowing"
  },
  "personality": [
    "Calm",
    "Strategic",
    "Loyal",
    "Fearless"
  ],
  "style": "Dark Fantasy",
  "clothing": {
    "upper": "Black leather corset",
    "lower": "Long armored skirt",
    "boots": "Steel boots",
    "cape": "Dark red cape"
  },
  "armor": {
    "type": "Mythril",
    "color": "Black and Silver",
    "details": "Dragon engravings"
  },
  "weapon": {
    "type": "Great Sword",
    "name": "Night Eclipse",
    "material": "Obsidian",
    "magic": "Shadow Flames"
  }
}

import random
import json

hair_colors = [
    "Silver",
    "Black",
    "White",
    "Blue",
    "Pink",
    "Golden"
]

eye_colors = [
    "Red",
    "Blue",
    "Purple",
    "Emerald",
    "Amber"
]

classes = [
    "Knight",
    "Mage",
    "Samurai",
    "Assassin",
    "Paladin",
    "Archer"
]

armors = [
    "Dragon Armor",
    "Mythril Armor",
    "Shadow Armor",
    "Crystal Armor"
]

weapons = [
    "Long Sword",
    "Katana",
    "Magic Sword",
    "Rapier",
    "Great Sword"
]

personalities = [
    "Brave",
    "Calm",
    "Intelligent",
    "Cold",
    "Kind",
    "Strategic",
    "Loyal",
    "Determined"
]

character = {
    "Class": random.choice(classes),
    "Hair": random.choice(hair_colors),
    "Eyes": random.choice(eye_colors),
    "Armor": random.choice(armors),
    "Weapon": random.choice(weapons),
    "Personality": random.sample(personalities, 3)
}

print(json.dumps(character, indent=4))

Create a highly detailed female fantasy character.

Requirements:

• Beautiful anime style
• Ultra detailed
• 8K quality
• Cinematic lighting
• Full body
• Dynamic pose
• Highly detailed face
• Highly detailed eyes

Appearance:
- Long elegant hair
- Bright expressive eyes
- Athletic body
- Graceful posture

Clothing:
- Detailed fantasy outfit
- Premium fabrics
- Gold embroidery
- Decorative belts
- Cape
- Gloves
- Boots

Armor:
- Ornate shoulder armor
- Chest plate
- Arm guards
- Leg armor
- Mythril or Dragon Steel
- Magical glowing runes

Weapon:
- Legendary sword
- Glowing blade
- Ancient engravings
- Floating magical particles
- Jewel embedded hilt

Style:
- Dark Fantasy
- Medieval Fantasy
- JRPG
- Genshin Impact inspired
- Final Fantasy inspired

Personality:
- Calm
- Elegant
- Intelligent
- Fearless
- Protective
- Loyal

Background:
Standing on an ancient castle bridge during sunset with magical particles floating in the air.
