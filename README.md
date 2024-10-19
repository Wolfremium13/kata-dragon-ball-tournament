# 💫 Kata Dragon Ball Sparking! ZERO Tournament

![Dragon Ball Sparking! ZERO](./docs/DBSZ-banner.jpg)

## Challenge

The latest Dragon Ball video game is here! It's called Dragon Ball: Sparking! ZERO. Simulate a Martial Arts Tournament,
in the purest style of the saga, where different fighters will participate, and the system will decide who the winner
is using Test Driven Development (TDD).

### 🥋 Fighters

- Name.
- Three attributes: speed, attack, and defense (with values ranging from 0 to 100 that you will choose).
- Each fighter starts a battle with 100 health.

### 🥊 Battle

- Each battle is between 2 fighters.
- The fighter with the highest speed starts attacking.
- Damage is calculated by subtracting the defender's defense from the attacker's attack power.
- The opponent always has a 20% chance to dodge the attack.
- If the defense is higher than the attack, they receive only 10% of the attack damage.
- After each turn and attack, the opponent loses health.
- The battle ends when a fighter loses all their health.

### ☀️ Tournament

- A tournament is only valid if the number of fighters is a power of 2.
- The tournament must create random pairs in each round.
- Fighters face each other in elimination rounds.
- The winner moves on to the next round until only one remains.
- You must display in the console everything that happens in the tournament, as well as the final winner.

Reference at **[retosdeprogramacion.com/roadmap](https://retosdeprogramacion.com/roadmap)**.