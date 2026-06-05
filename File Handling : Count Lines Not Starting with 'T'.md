# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```py
count = 0
with open("story.txt", "r") as file:
    for line in file:
        if line.strip() and not line.lstrip().startswith('T'):
            count += 1
print("Sum :", count)
```

## Text file
```
A deep mystery remained unsolved in the quiet town.
Rain poured heavily against the window panes all evening.
Shadows elongated across the old wooden floorboards.
Everyone in the house felt a sudden chill in the air.
Nobody dared to speak or make a single sound.
Suddenly, a distant knock echoed from the front door.
The clock struck midnight with a loud chime.
Then, the lights flickered and went out completely.
A deep mystery remained unsolved in the quiet town.
Rain poured heavily against the window panes all evening.
Shadows elongated across the old wooden floorboards.
Everyone in the house felt a sudden chill in the air.
Nobody dared to speak or make a single sound.
Suddenly, a distant knock echoed from the front door.
The clock struck midnight with a loud chime.
Then, the lights flickered and went out completely.
A deep mystery remained unsolved in the quiet town.
Rain poured heavily against the window panes all evening.
Shadows elongated across the old wooden floorboards.
Everyone in the house felt a sudden chill in the air.
Nobody dared to speak or make a single sound.
Suddenly, a distant knock echoed from the front door.
The clock struck midnight with a loud chime.
Then, the lights flickered and went out completely.
```

## Output
<img width="250" height="61" alt="image" src="https://github.com/user-attachments/assets/292a40ae-0af1-46e2-8f01-077d17e9e658" />

## Result
Thus, the program that counts the number of lines in a text file story.txt that do not start with the alphabet 'T' was executed successfully.
