🐜 Ants Vs. SomeBees
1. 🧠 Introduction

This project was completed as part of CS 61A: Structure and Interpretation of Computer Programs at UC Berkeley, taught by Professor John DeNero in Fall 2024.

This project involves creating a tower defense game called Ants Vs. SomeBees. As the ant queen, you populate your colony with the bravest ants you can muster. Your ants must protect their queen from the evil bees that invade your territory.

Irritate the bees enough by throwing leaves at them, and they will be vanquished. Fail to pester the airborne intruders adequately, and your queen will succumb to the bees' wrath.

    🎮 Inspired by PopCap Games’ Plants Vs. Zombies.

2. 🎮 The Game

A game of Ants Vs. SomeBees consists of a series of turns:

    🐝 Bees may enter the colony.

    🐜 Ants are placed to defend it.

    Each insect takes an action:

        Bees try to move forward or sting.

        Ants perform actions like gathering food or attacking bees.

🏆 Win Condition:

    All bees are vanquished.

💀 Lose Condition:

    A bee reaches the end of a tunnel.

4. ▶️ Playing the Game

You can run the game in either text-based mode or graphical mode.
📝 Text Mode

$ python3 ants_text.py

🖼 GUI Mode

$ python3 ants_gui.py

🔧 Command-line Options

usage: ants_text.py [-h] [-d DIFFICULTY] [-w] [--food FOOD]

Play Ants vs. SomeBees

optional arguments:

-h, --help         show this help message and exit

-d DIFFICULTY      sets difficulty (test/easy/medium/hard/extra-hard)

-w, --water        loads a full layout with water

--food FOOD        starting food amount for testing
