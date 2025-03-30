# Knight of the Godblaster: A D&D-Style RPG

**Knight of the Godblaster** is a text-based RPG inspired by *Dungeons & Dragons 5th Edition*. As a junior knight of the Multiversal Order, you must rescue the twin gods Suma and Drillus from the shadow demon Zrugix in the perilous world of Sycaria. Navigate through a castle, manage your inventory, engage in tactical combat, and make choices that determine your fate!

---

## Features

- **D&D-Inspired Mechanics**:  
  - Roll virtual dice (D4 to D20) for stat generation, combat, and skill checks.  
  - Character creation with procedurally generated ability scores, modifiers, and saving throws.  

- **Dynamic Combat System**:  
  - Turn-based battles with initiative rolls, attack modifiers (Strength/Dexterity), and enemy AI.  
  - Weapon classes with damage dice (e.g., Godblaster deals 2d12 ranged damage).  

- **Interactive Storytelling**:  
  - Choice-driven narrative with multiple endings.  
  - Explore procedurally generated rooms with ASCII art maps.  

- **Inventory Management**:  
  - Weight-based inventory system with buy/sell functionality.  
  - Over 50+ weapons, armor, and items (e.g., E-Reader for maps, glowing mushrooms for loot).  

- **Immersive UI**:  
  - ANSI-colored headers, stat sheets, and ASCII visualizations.  
  - Input validation for menu navigation and numerical choices.  

---

## Installation & Setup 

### Requirements
- **Python 3.6+**  
- Jupyter Notebook or Google Colab  
- Required packages: `random`, `copy`, `google.colab` (for Colab screen clearing)  

### How to Run
1. Clone the repository or download `game.ipynb`.  
2. Open the notebook in **Jupyter** or **Google Colab**.  
3. Run all cells. The game starts automatically!  

---

## Gameplay Instructions

### Character Creation  
- Roll 4d6 for ability scores (Strength, Dexterity, etc.).  
- Choose between Strength or Dexterity for attack modifiers.  
- Equip starting gear, including the Godblaster and Leather Armor.  

### Exploration  
- Navigate Zrugix’s castle across 5 procedurally generated rooms.  
- Search for loot, solve puzzles, and avoid traps.  
- Use the **E-Reader** to view your location on the map.  

### Combat  
- Engage in turn-based battles against Zrugix.  
- Use weapons with **Finesse**, **Ranged**, or melee attack types.  
- Heal by sacrificing items to a "swirling void" (random d12 rolls).  

### Endings  
- **Good Ending**: Defeat Zrugix and rescue the gods.  
- **Bad Ending**: Fall in battle and face eternal darkness.  
- **Secret Ending**: Discover hidden choices!  

---

## Technical Details 

### Code Structure
- **Classes**: `Item`, `Weapon`, `E_reader` for inventory items.  
- **Dice Functions**: `roll_d4()`, `roll_d20()`, etc., with customizable rolls.  
- **Game Flow**:  
  - Part 1: City exploration (shops, inventory management).  
  - Part 2: Castle navigation (room puzzles, loot drops).  
  - Part 3: Final boss battle against Zrugix.  

### Dependencies
- Built with Python’s standard libraries.  
- Uses ANSI escape codes for colored text and headers.  

---

## Credits & License

- **Author**: Aadhya Anand  
- **Inspired By**: Dungeons & Dragons 5th Edition (Wizards of the Coast).  
- **ASCII Art**: Generated via [patorjk.com](https://patorjk.com/software/taag/).  
- **License**: MIT License (see `LICENSE`).  
- **Note**: D&D is a trademark of Wizards of the Coast. This project is a fan creation. 
