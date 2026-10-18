# Dev Journal - Lienu

I'm a student in France pursuing a **BTS SIO** (a French 2-year post-secondary technical degree in IT Services, roughly equivalent to a US Associate Degree / UK HND), specializing in **Software Development (SLAM track)**, 2026–2028.

Goal: becoming a back-end / full-stack software developer.

This repository is where I track my technical progress publicly and consistently what I'm learning, my projects, my struggles.

## Target stack
- C# / .NET (aligned with my BTS curriculum)
- HTML / CSS
- Python (algorithmic practice on Exercism)
- SQL (to be learned in class)

## Log

### September 2, 2026 - Day 1 : First real exercise (Exercism: Lasagna)
First day of my BTS SIO (Software Development track). Created this repository to track my progress.
This week's goals: Python fundamentals on Exercism, starting a real personal project.

Completed the "Lasagna" exercise on Exercism (Python). Made several mistakes:
missing `return` statements in all three functions, a variable name typo and incorrect logic in one function.

Important realization: I previously learned Python/C++ mostly by copying
AI-generated code and trying to memorize what it did, rather than writing
code from scratch myself. This explains today's mistakes. I understood
code when reading it, but hadn't built the habit of producing it independently.

Changing method starting now: attempt exercises alone first (even if wrong),
only use AI to review code I've already written or explain concepts I don't
understand and never to generate solutions upfront.

### Early September 2026 - Python exercises (Exercism)
Completed "Ghost Gobble Arcade Game", "Triangle" and "Collatz Conjecture".
Main mistakes: overwriting function parameters instead of using them, mixing
up `and` / `or` precedence, and forgetting that a failed condition must return
`False` rather than nothing.
Lesson: write the steps in plain language first, then translate them to code.

### September 2026 - First steps in C#
Variables and types, `Console.ReadLine()`, arithmetic operators.
Discovered that C# is statically typed, and hit a `DivideByZeroException`
by entering 0 as the second number. Next step: check the value before dividing.

### September 2026 - HTML and CSS
Followed two guided exercises in class and applied the method to my own
project, `game-dev-journal`: a homepage with header, nav, main, footer,
flexbox layout and a shared stylesheet, then separate pages for projects and contact.

### October 15, 2026 - First push of the project
Pushed `index.html`, `style.css`, `projets.html` and `contact.html` to GitHub.

### October 15-18, 2026 - Loops in C#
Learned `while` and `for`. Exercise: sum of the integers from 1 to N.
I filled in a trace table by hand first. My mistake was trying to find a
clever formula instead of using the loop variable `i`. A hint was needed for
the `while` version; I wrote the `for` version alone, using the course for the syntax.
Lesson: when stuck, trace the example by hand and look at what repeats.

### Next
- Finish the OWASP pages for my workshop (due October 25).
- Sum of the even numbers from 1 to N (loop + `if` + modulo).
- Add the project sections to `projets.html`.
