# 🎯 Number Guessing Game 🎲

A **fun and interactive** Python-based number guessing game where you try to guess a randomly generated number within a limited number of attempts.

---

## 🌟 Features
✅ Choose difficulty level: **🟢 Easy (10 attempts) 🔴 Hard (5 attempts)**  
✅ Get **hints** if your guess is too high or too low  
✅ Win by guessing the **correct number** within the allowed attempts  
✅ Simple and **customizable** game logic  

---

## 🎮 How to Play
1️⃣ Run the script.  
2️⃣ Choose your **difficulty level** by typing `easy` or `hard`.  
3️⃣ Enter your **guesses** until you find the correct number or run out of attempts.  

---

## 🔧 Requirements
- 🐍 **Python 3.x**

---

## 🚀 Installation & Usage
```sh
# Clone the repository
git clone https://github.com/AREEB-08/number_guessing_game.git

# Navigate to the directory
cd number_guessing_game

# Run the script
python game.py
```

---

## 🎭 Example Gameplay
```
🎲 Let me think of a number between 1 and 50.
Choose level of difficulty: type 'easy' or 'hard': easy
🔢 You have 10 attempts remaining to guess the number.
🎯 Guess a number: 25
📉 Your guess is too high.
🔄 Guess again.
...
🎉 Your guess is right! The answer is 42.
```

---

## 🛠️ Customization
Want to modify the game? Here’s how you can customize it:
- **Change the number range** by modifying `random.randint(1, 50)` in `game.py`.
- **Adjust difficulty levels** by changing `EASY_LEVEL_ATTEMPTS` and `HARD_LEVEL_ATTEMPTS`.
- **Enhance user experience** by adding colors using `colorama`:
  ```sh
  pip install colorama
  ```
  Then, modify the `print` statements to use colors!
  ```python
  from colorama import Fore
  print(Fore.GREEN + "Your guess is right! The answer is 42.")
  ```

---

## 🤝 Contributing
Feel free to **fork** this repository and submit **pull requests** with improvements or bug fixes.

---

## 📜 License
This project is **open-source** and available under the **MIT License**.

---

### 🔗 [GitHub Repository: AREEB-08](https://github.com/AREEB-08) 🚀

