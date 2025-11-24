# 🏆 Hackerrank:Runner-Up Score Finder in Python

## 🎯 AIM:
To write a Python program that takes a list of scores from participants and finds the **runner-up score** (i.e., the second-highest score), eliminating any duplicates.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a variable `n` and get its value from the user (number of participants)
3. Read the list of `n` scores from the user using `input().split()` and convert them to integers
4. Store the scores in a list
5. Use `set()` to remove any duplicate scores
6. Convert the set back to a list and sort it in ascending order
7. Print the second-last element of the sorted list (i.e., the runner-up score)
8. **Stop**

---

## 💻 PROGRAM:

```
n = int(input())
scores = list(map(int, input().split()))
unique_scores = set(scores)
unique_scores.remove(max(unique_scores))
runner_up = max(unique_scores)
print(runner_up)

```

## OUTPUT
<img width="646" height="258" alt="image" src="https://github.com/user-attachments/assets/0630d2ea-abe6-4e49-8c82-2996b707fc6e" />

## RESULT
Thus, the python program to find the runner-up score from a list of scores
has been executed successfully.
