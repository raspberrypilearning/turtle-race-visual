## Race the turtles
--- task ---

In another `for` loop, make the first turtle move forwards a random distance, 100 times.

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 47
line_highlights: 
---
for turn in range(100):
    ada.forward(randint(1, 5))
--- /code ---

--- /task ---

--- task ---

Now make the other turtles race with the first turtle.

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 49-51
line_highlights: 
---
for turn in range(100):
    ada.forward(randint(1, 5))
    bob.forward(randint(1, 5))
    eve.forward(randint(1, 5))
    kai.forward(randint(1, 5))
--- /code ---

--- /task ---

--- task ---

You can change the distance moved (`randint(1, 5)`) and the number of times moved (`range(100)`) to see what effect that has on the race.

--- /task ---