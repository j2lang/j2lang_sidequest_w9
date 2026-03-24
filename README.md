## Project Title

Side Quest Week 9 Debug Screen

---

## Group Number/Members

Joanne Lang j2lang 21066111

---

## Description

Generates a level using JSON data; uses loops to dynamically place obstacles/platforms. Second level loads automatically when the first is finished.

---

## Interaction Instructions

Land on green to advance • Move: A/D or ←/→ • Jump: Space/W/↑ • Next: N

---

## Assets

N/A

---

## GenAI

I inputted the .js files and side quest instructions, and ChatGPT gave me explanations of the concepts and .js solutions to try for what I wanted to implement.
•	Gave it more input – copy pasted in the starting Example 5 files to provide more context after having asked it to explain the side quest instructions; this was to give it more context so it could give a better, more specific response to my initial prompt asking it to explain the instructions
•	Still didn’t fully understand its explanation, so prompted it to further clarify what the difference was between the arrays approach/JSON approach
•	Tried implementing a given JSON approach, but the blob couldn’t physically jump high enough to reach the next platform; prompted it for ways to fix this
•	Prompted for a way to make gap between platforms big enough for the blob to get stuck but not fall through; the result was technically wrong (gave solution for gap slightly bigger than blob width instead of slightly smaller, but I liked this so I kept it)
•	When adding “win” platforms, prompted it for exactly where in blobPlayer.js I would need to add the given code snippet
•	Prompted it to fix the mistake in my code by giving it all my updated files (Live Server screen was just blank white, needed to fix this)
•	Prompted it to fix the level transition glitch

---

## Reference List

N/A

---
