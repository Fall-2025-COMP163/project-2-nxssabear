
# COMP 163 - Project 2: Character Abilities Showcase

 Name: Vanessa Gray
 
 Date: 13-Nov-2025

 AI Usage: AI assisted with overridden attack logic, debugging the Mage fireball and Rogue critical hit system, creating the bonus Necromancer class, and writing this README file.

# ✨ Project Overview

The Character Abilities Showcase demonstrates inheritance, polymorphism, method overriding, and special abilities across multiple fantasy RPG-style classes. Each character features unique combat mechanics, stat profiles, and special moves. The included battle simulator allows characters to fight each other to test damage calculations and class differences.

# 🛡️ Features

## 1. Multi-Level Inheritance Structure

Characters follow a clear hierarchy:

Character → base stats & attacks

Player → adds class info, level, experience

Warrior, Mage, Rogue, Necromancer → specialized child classes

Each subclass overrides attack behavior and includes a signature ability.

## 2. Polymorphic Combat System

All characters share the same method name (attack()), but each class behaves differently:

Warriors hit harder with physical power

Mages deal magic-based damage

Rogues can land critical hits

Necromancers drain life with dark magic

The same call → different output depending on the class.

## 3. Special Abilities

Each class includes one powerful, unique move:

Warrior: Power Strike 💥

Mage: Fireball 🔥

Rogue: Sneak Attack 🗡️

Necromancer (Bonus): Drain Life 🩸

Abilities greatly affect damage output and strategy.

## 4. Weapon Composition System

A standalone Weapon class is included to demonstrate HAS-A relationships.

Weapons have:

A name

A damage bonus

A display method

Characters can have weapons without inheriting from them.

## 5. Battle Simulator

The provided SimpleBattle class (not modified) simulates:

Stat display

Attack rounds

Results comparison

Automatic winner declaration

Perfect for testing polymorphism and damage interactions.

# 🌟 Creative Touches

Bonus Class: Necromancer — A fully custom class with lifesteal mechanics and dark-magic combat.

Enhanced stat formatting for cleaner, stylized output.

Distinct damage formulas for each class, emphasizing RPG character variety.

Critical hit system for the Rogue, adding unpredictability and flavor.

These additions expand the system beyond requirements and make each character feel unique.

# 📝 Notes

All class methods are structured for readability and testability.

Health never drops below 0 due to safety logic in take_damage().

The project is easily expandable — new classes, abilities, or weapons can be added with minimal changes.

The battle simulator was not modified, as instructed.

# ▶️ How to Run

Run the program from your terminal using:

python project2_starter.py
