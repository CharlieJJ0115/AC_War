# Group 23 Final Project

## Demo Video

[![Demo Video](https://img.youtube.com/vi/UP3DsW4Y3Qc/0.jpg)](https://www.youtube.com/watch?v=UP3DsW4Y3Qc)

---

## Features

### Change Mechanism of the Game
* From **Defense-only** to **both Defense and Offense**

> Players must defend their own tower while attempting to destroy the opponent's tower.  
> The player who successfully breaks through the defense and destroys the main tower wins the game.

---

### Character Features

#### What is a Character
1. Characters can **attack** and **be attacked**.
2. Characters move using a **Path Finding Algorithm** and stop when attacking.

> **Path Finding Method:**  
> The path is updated according to the character's position and the opponent tower's state (alive or destroyed).  
> If an opponent is detected, the character will move toward and attack it.

---

#### Types of Characters
1. Fly (Remote)  
2. Melee (Ground)  
3. Remote (Fly or Ground)  
4. Tower  

---

#### Differences Between Types
1. **Fly units** can move directly to their target without considering obstacles.  
2. **Fly units** cannot be hit by **Melee units**.  
3. **Towers** can attack all types of characters.  

---

#### Individual Character Features
1. **Stone Titan**
   * Only attacks opponent towers
   * Has a special attack effect

2. **CS Student**
   * Splits into four students

3. **Shadow Sniper**
   * Has a special attack effect

---

### Animation
* Opening Animation  
  * Tells the player a short story  
* Start Scene Animation  

---

### UI / UX
* **Warning message** appears if a player violates rules  
* **Skip button** for players who want to skip animations  
* Interface for two players to:
  * Input their names
  * Choose characters
* Character introduction page showing:
  * stats
  * advantages
  * disadvantages
* Convenient way to choose:
  * where to deploy characters
  * which characters to send to battle

---

## Individual Contributions

| 江善有 | 林君翰 | 施閔智 |
|------|------|------|
| Design Character Class | Design Character Class | Animation |
| Character Appearance | Character Appearance | UI/UX |
| Character Features | Character Features | Scene Design & Mechanism |
| 33% | 33% | 33% |
