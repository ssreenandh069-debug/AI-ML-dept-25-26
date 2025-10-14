# AI-ML-dept-25-26

## PYTHON REVISION

### TASK 1: Emoji Mood Analyzer (Beginner – Strings & Dicts)

**Goal:**  
Take a sentence as input and decide if it's positive, negative, or neutral based on words/emojis.

**Concepts Revised:**  
Strings, dictionaries, loops, conditionals, basic logic.

**Hint:**
- Make a dict like `{"love": 1, "😍": 1, "hate": -1, "😫": -1}`
- Loop through keys, and count how many appear in the sentence.
- Compare positive vs negative counts.

**Starter Template:**
```python
sentence = input("Enter a sentence with emojis: ")

mood_dict = {"love": 1, "😍": 1, "happy": 1, "hate": -1, "😫": -1, "sad": -1}

# TODO: initialize positive = 0, negative = 0
# TODO: loop through mood_dict keys and count how many are in sentence
# TODO: compare and print result like "Overall Mood: Positive/Negative/Neutral"
```

### TASK 2: Random Story Generator (Intermediate – Lists & Random)

**Goal:**  
Generate a random 2-line funny story by mixing random characters, places, and actions.

**Concepts Revised:**  
Lists, random module, string formatting.

**Hint:**
- Create 3–4 lists: characters, places, objects, actions.
- Use `random.choice()` to pick one from each and build a sentence.
- Run it multiple times for new results.

**Starter Template:**
```python
import random

characters = ["a sleepy panda", "an alien", "a pirate", "a robot"]
places = ["in the jungle", "on Mars", "at a tech fest", "in the library"]
objects = ["a laptop", "a treasure map", "a sandwich", "a phone"]
actions = ["started coding", "fell asleep", "built a rocket", "lost their WiFi"]

# TODO: use random.choice() to pick one from each list
# TODO: print something like:
# "Once upon a time, ___ found ___ ___ and ___!"
```

**Bonus Twist:**  
Add an input:  
```python
how_many = int(input("How many stories do you want? "))
```
and loop that many times.

### TASK 3: Treasure Hunt Game (Logic & Loops)

**Goal:**  
Hide a treasure randomly in a list of 5 places. Player guesses until they find it.

**Concepts Revised:**  
Loops, conditionals, user input, indexing, random.

**Hint:**
- Create a list: `["_", "_", "_", "_", "_"]`
- Randomly choose a treasure position (index).
- Let the user guess (1–5) until they find it.
- After each guess, tell them "too left" or "too right".

**Starter Template:**
```python
import random

map = ["_", "_", "_", "_", "_"]
treasure = random.randint(0, 4)

found = False

while not found:
    guess = int(input("Guess the position (1-5): ")) - 1
    
    # TODO: check if guess == treasure
    # TODO: print hints like "Too left!" or "Too right!"
    # TODO: replace guessed position with "O" for tried spots
    # TODO: print current map after each guess

print("You found the treasure! 🏆")
```

### Submission Requirements:
- Code files of all the code, named `1.py`, `2.py`, `3.py`
- This would be submitted via github (details of which would be given later)... Github seekhna start karlo
