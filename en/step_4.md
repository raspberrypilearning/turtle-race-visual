## Race the turtles

--- task ---

Make the first turtle move forward a random distance, 100 times.

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

Now add the other turtles to the race.

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

![turtle race](images/turtle-racing.png)

--- task ---

Try changing the numbers in `randint(1, 5)` and `range(100)` to see what happens.

--- /task ---
