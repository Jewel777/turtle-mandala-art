# turtle-mandala-art
🎨 Colorful mandala-style turtle graphics pattern using overlapping circles and rotational symmetry in Python
# 🐢 Turtle Graphics Mandala Pattern

This project uses Python's built-in `turtle` module to draw a **visually stunning mandala-style pattern** composed of overlapping circles with vibrant colors. It serves as an artistic demonstration of how simple geometric instructions and loops can produce complex symmetrical designs.

---

## 🎯 Project Objective

To explore turtle graphics through:
- Symmetry and rotational patterns
- Colorful layered shapes
- Animation speed and precision control

---

## 🖼️ Visual Output

The design features:
- A **blue filled circular spiral** in the center
- Additional **rotating loops of circles** from different compass points (top, bottom, left, right) in colors: pink, gold, red, and green
- A final **white large circular rotation** for artistic flair

---

## 🐍 Run the Code

### Option 1: As a Python script
Save the code as `mandala_turtle.py` and run:
```bash
python mandala_turtle.py
Option 2: In a Jupyter Notebook
Paste the code into a cell and run interactively (must be on a system with GUI support).

🧠 Learning Outcomes
This project is ideal for:

Beginners learning Python turtle graphics

Students exploring symmetry, loops, and basic animation

Artists and developers creating generative art with code

📜 Requirements
Python 3.x

No external libraries required

A system with GUI (Turtle uses tkinter for drawing)

🧩 Source Code Snippet
python
Copy
Edit
from turtle import *
bgcolor('black'); pencolor('white'); speed(1000)
fillcolor('blue'); begin_fill()
for i in range(1,73): circle(50); left(5)
end_fill()

for color, pos in [('pink', (0, 100)), ('gold', (0, -100)), 
                   ('red', (100, 0)), ('green', (-100, 0))]:
    pencolor(color); penup(); goto(pos); pendown()
    for i in range(1,73): circle(50); left(5)

home(); pencolor('white')
for i in range(1,73): circle(100); left(50)
done()
👨‍💻 Author
Md Julfiker Ali Jewel
Graduate Researcher | Software Programmer | AI Enthusiast
Website • Email

🪪 License
This project is open-source and free to use for learning and creative purposes.



