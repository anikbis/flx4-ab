# Contributing to FLX4 AB

Thanks for helping. Any of these are useful: bug reports, mix feedback, controller test results, code review and pull requests.

## Running it

There is no build step. Open `index.html` in Chrome or Edge.
To test AI stems, serve the folder over `http://localhost` (for example `python3 -m http.server`), because some browsers restrict features on `file://` pages.

## Reporting a controller problem

Please include:
- Your OS and browser version
- The control you pressed and what happened
- The MIDI line shown at the bottom right of the library when you pressed it (for example `Note 8·32 = 127`)

## Reporting a mix that sounded wrong

Please include the two tracks' BPM and key (shown in the library), the transition style, and the note
the app showed when the mix started (it explains the AI's decisions). A short description of what sounded off
(volume jump, clashing vocals, bad timing, harsh sound) helps more than a rating.

## Pull requests

- Keep the app a single, dependency-free HTML file unless there's a strong reason not to.
- Describe what you changed and how you tested it (with or without a real controller).
- Audio changes: say how you checked for clicks, clipping and timing.
- Never include copyrighted music in the repository.
