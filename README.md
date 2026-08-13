# 🎮 Python RPG

A small role-playing game written in Python.

This project is my first RPG developed with Python. The goal is to build a simple but expandable RPG while learning and applying concepts such as object-oriented programming, game logic, combat systems and project structure.

## 🚧 Project Status

**Work in Progress**

The project is currently under development. New features and improvements will be added over time.

## 🎯 Goals

The main goals of this project are:

* Learn and improve Python programming
* Practice object-oriented programming
* Build a modular RPG architecture
* Create a combat system
* Implement characters, enemies and items
* Add an inventory system
* Add character progression with experience and levels
* Build an expandable game world

## 🛠️ Technologies

* **Python 3**
* Object-Oriented Programming (OOP)
* Git & GitHub

## 📁 Project Structure

```text
Python-RPG/
│
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt
│
├── src/
│   └── rpg/
│       ├── main.py
│       │
│       ├── core/
│       │   ├── game.py
│       │   └── battle.py
│       │
│       ├── characters/
│       │   ├── character.py
│       │   ├── player.py
│       │   └── enemy.py
│       │
│       ├── items/
│       │   ├── item.py
│       │   ├── weapon.py
│       │   └── potion.py
│       │
│       ├── world/
│       │   ├── map.py
│       │   ├── room.py
│       │   └── npc.py
│       │
│       └── utils/
│           └── helpers.py
│
├── tests/
│   ├── test_character.py
│   ├── test_battle.py
│   └── test_items.py
│
└── assets/
    ├── images/
    └── sounds/
```

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/A-Koubaa/Python-RPG.git
cd Python-RPG
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the virtual environment.

### Windows

```bash
.venv\Scripts\activate
```

### Linux / macOS

```bash
source .venv/bin/activate
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

## 🎮 Running the Game

Start the game with:

```bash
python -m rpg.main
```

## 🧙 Planned Features

* [ ] Character creation
* [ ] Player statistics
* [ ] Enemy system
* [ ] Turn-based combat
* [ ] Different enemy types
* [ ] Experience and levels
* [ ] Inventory
* [ ] Weapons
* [ ] Potions
* [ ] Shops
* [ ] NPCs
* [ ] Quests
* [ ] Game world
* [ ] Save and load system

## 🧪 Testing

Tests are located in the `tests/` directory.

Run the test suite with:

```bash
python -m pytest
```

## 📚 What I Am Learning

This project is mainly a learning project. It helps me practice:

* Python
* Classes and objects
* Inheritance
* Encapsulation
* Modules and packages
* Game loops
* State management
* Git and GitHub
* Software architecture
* Unit testing

## 📄 License

This project is licensed under the MIT License.

See the `LICENSE` file for more information.

## 👤 Author

**A-Koubaa**

GitHub: https://github.com/A-Koubaa
