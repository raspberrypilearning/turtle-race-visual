## Add a track

--- task ---

Send the turtle to the top of the screen and speed it up

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 32
line_highlights: 
---
penup()
goto(-140, 140)
speed(10)
--- /code ---

--- /task ---

--- task ---

Write numbers from `0` to `11` across the top of the screen.

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 36
line_highlights: 
---
for step in range(12):
    write(step, align='center')
    forward(20)
--- /code ---
--- /task ---

--- task ---

Change the number `12` to see how this changes the numbers that are drawn.

--- /task ---

--- task ---

Draw lines beneath each of the numbers, to show the track

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 36
line_highlights: 38-44
---
for step in range(12):
   write(step, align='center')
    right(90)
    forward(10)
    pendown()
    forward(150)
    penup()
    backward(160)
    left(90)
    forward(20)
--- /code ---

--- /task ---

