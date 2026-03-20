# 🍵 Focus — Pomodoro Timer
A cozy, distraction-free study timer built entirely with vanilla JavaScript. No frameworks, no dependencies — just a single HTML file you can open in any browser.


Preview
Day Mode	Night Mode
Show Image
Show Image
Add your screenshots to a /screenshots folder to display them here.

Features
Timer

Classic Pomodoro technique — 25 min focus, 5 min break by default
Fully customizable study (1–90 min) and break (1–30 min) durations
Visual progress ring that depletes as time passes
Session dots inside the clock track your progress through each set of 4
Musical chimes signal the end of each session or break
Themes

Day mode — warm watercolour study desk illustration
Night mode — cozy moonlit lo-fi bedroom illustration
Smooth transition between themes, preference saved automatically
Sound

Rain — white noise with low bass rumble
Lo-fi — warm chord drone
Deep Focus — binaural-style tone (200Hz + 240Hz)
All sounds generated via Web Audio API, no audio files needed
Mute toggle with keyboard shortcut
For Students

Rotating study tips based on proven methods — Active Recall, Spaced Repetition, Feynman Technique, and more
Session task list — add tasks before you start, check them off as you go
Daily stats — sessions completed, total focus time, and day streak
Focus mode — hides everything except the clock for zero distraction
General

All settings, tasks, and stats saved to localStorage
Fully offline after first load
Keyboard shortcuts for everything
Clean, responsive layout
Keyboard Shortcuts
Key	Action
Space	Play / Pause
R	Reset timer
M	Mute / Unmute
T	Toggle day / night theme
S	Open / Close settings
Esc	Close settings
Getting Started
No install. No terminal. Just open the file.

bash
git clone https://github.com/yourusername/focus-timer.git
cd focus-timer
open index.html
Or download the zip and open index.html directly in Chrome, Firefox, Safari, or Edge.

Project Structure
focus-timer/
└── index.html    # The entire app — HTML, CSS, and JS in one file
Built With
Vanilla JavaScript — no frameworks or libraries
Web Audio API — procedural ambient sounds and chimes
CSS backdrop-filter — frosted glass card effect
localStorage — persistent stats, tasks, and settings
SVG — animated progress ring and clock tick marks
Google Fonts — Lora · Outfit · Inconsolata
© 2025 Saurav Kunwar. All rights reserved.
