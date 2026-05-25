# ⚡ THESEUS — Claude Shannon's Maze Mouse

> *"The intelligence was never in the mouse. It was in the floor."*

A faithful interactive simulation of Claude Shannon's 1950 electromechanical maze-solving mouse, **Theseus**, built at Bell Labs.

## The History

In 1950, information theorist Claude Shannon wired 90 telephone relays beneath a 5×5 grid. A copper-whiskered bar magnet on three wheels — dubbed Theseus — would blunder through a maze by trial and error. Sensors beneath the floor recorded every move. On the second run, Theseus navigated flawlessly. It had *learned*.

This was one of the world's first demonstrations of machine learning.

## The Algorithm

Shannon used a variant of **Trémaux's algorithm** (depth-first search):
- **Exploration phase**: Turn-left preference, explore clockwise. Each cell's relay stores the last exit direction.
- **Goal phase**: When cheese is found, the relay chain from start→goal is already correct. Follow it perfectly.

## Play

1. Click **▶ START** — watch Theseus explore the maze (yellow)
2. Click **⚡ 2ND RUN** — watch the perfect relay-guided solve (green trace)
3. Try **14×14** or **18×18** for a brutal maze

## Built With

Plain HTML/CSS/JS. Zero dependencies. Wilson's algorithm for perfect maze generation.
