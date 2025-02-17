[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/AUMDT7Sv)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=18254572&assignment_repo_type=AssignmentRepo)
# 🤿 Submarine Adventure: Variable Debug Edition 🚨  

## HINT: To Check for Yes/No
```python
likes_math = input("Do you like math? (yes/no): ")
if likes_math == "yes":
    ...
else:
    ...
```
---

## **Day 1: Dive Starter**  
**Debug Mission 🔧**  
This code doesn't work! Copy it and figure out why.
```python  
depth = "200"  
current_depth = depth + 100 
print("Depth:", current_depth, "meters")  
```  
*Test Cases:*  
- If `depth = 100` → Should print *200 meters*  
- If `depth = "200"` → Should **not** print *200100*  

**Story Continuation 🎨**  
Add code to check if oxygen is low (yes/no). If yes, add 10 oxygen and print "Emergency air!"  

---

## **Day 2: Cave Choice**  
**Debug Mission 🔧**  
This code doesn't work! Copy it and figure out why.
```python  
cave_temp = "12"  
safe_temp = cave_temp - 2  
print("Safe temp:", safe_temp)  
```  
*Test Cases:*  
- If `cave_temp = "10"` → Should print *8*  
- If `cave_temp = "five"` → Crash expected 💥  

**Story Continuation 🎨**  
Two tunnels appear! Ask the crew: "Go left? (yes/no)". Use their answer in an `if` to change *one* submarine status.  

---

## **Day 3: Treasure Security**  
**Debug Mission 🔧**  
This code doesn't work! Copy it and figure out why.
```python  
code = input("Code? (1-5): ")  
if code == 3:
    print("Open!")  
```  
*Test Cases:*  
- Input `3` → Should print *Open!*  
- Input Anything Else → Should **not** work  

**Story Continuation 🎨**  
Add a boolean `is_alarm_on`. If the wrong code is entered, set it to `True` and print "Intruder alert!"  

---

## **Day 4: Glowing Creature**  
**Debug Mission 🔧**  
This code doesn't work! Copy it and figure out why.
```python  
health = "80"  
damage = 20  
new_health = health - damage  # 😵 Broken math  
print("Health:", new_health)  
```  
*Test Cases:*  
- Should print *60*  
- Should **not** print *8020*  

**Story Continuation 🎨**  
A jellyfish glows! 🌟 Ask "Shine light? (yes/no)". Use a boolean to decide if it swims away.  

---

## **Day 5: Emergency Escape**  
**Debug Mission 🔧**  
This code doesn't work! Copy it and figure out why.
```python  
pressure = "1500"  
if pressure > 1000: 
    print("Leak detected!")  
```  
*Test Cases:*  
- If `pressure = "2000"` → Should warn  
- Should crash when comparing string to number  

**Story Continuation 🎨**  
Add a boolean `is_leaking`. Ask the crew "Seal doors? (yes/no)" to set it. If leaking, print "🚨 Danger!"  
