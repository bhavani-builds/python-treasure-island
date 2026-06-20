# 🏝️ Treasure Island

A text-based adventure game written in Python. Navigate through choices to find the hidden treasure — or meet your doom!

```
*******************************************************************************
          |                   |                  |                     |
 _________|________________.=""_;=.______________|_____________________|_______
|                   |  ,-"_,=""     `"=.|                  |
|___________________|__"=._o`"-._        `"=.______________|___________________
*******************************************************************************
```

---

## 🎮 How to Play

Run the game and follow the prompts. Every choice matters — one wrong turn and it's **Game Over**.

**The path to victory has 3 decisions:**

```
Crossroad  →  left ✅  |  right ❌
Lake       →  wait ✅  |  swim  ❌
Door       →  yellow ✅ | red ❌ | blue ❌
```

> Only one combination leads to the treasure. Can you find it?

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x — download from [python.org](https://www.python.org/downloads/)

### Run the game

```bash
# Clone the repository
git clone https://github.com/yourusername/treasure-island.git

# Navigate into the folder
cd treasure-island

# Run the game
python treasure_island.py
```

---

## 📁 Project Structure

```
treasure-island/
├── treasure_island.py   # Main game file
└── README.md            # This file
```

---

## 🗺️ Game Map

```
START
  │
  ├── left  ──► Lake
  │               │
  │               ├── wait ──► Island House
  │               │               │
  │               │               ├── 🔴 red    → Fire Room   (Game Over)
  │               │               ├── 🟡 yellow → Treasure!   (YOU WIN 🏆)
  │               │               └── 🔵 blue   → Beast Room  (Game Over)
  │               │
  │               └── swim ──► Angry Trout Attack (Game Over)
  │
  └── right ──► Hole (Game Over)
```

---

## 🛠️ Built With

- **Python 3** — no external libraries needed

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

Inspired by classic text adventure games. ASCII art ship included for atmosphere!
