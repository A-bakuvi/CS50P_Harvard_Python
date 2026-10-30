# CS50P: Introduction to Programming with Python

My solutions to the problem sets from Harvard's [CS50P](https://cs50.harvard.edu/python/), covering Python fundamentals through testing, file I/O, regular expressions and object-oriented programming.

## Problem sets

| Set | Topic | Problems |
|---|---|---|
| 0 | Functions, variables | einstein, faces, indoor, playback, tip |
| 1 | Conditionals | bank, deep, extensions, interpreter, meal |
| 2 | Loops | camel, coke, nutrition, plates, twttr |
| 3 | Exceptions | fuel, grocery, outdated, taqueria |
| 4 | Libraries and APIs | adieu, bitcoin, emojize, figlet, game, professor |
| 5 | Unit tests (pytest) | test_bank, test_fuel, test_plates, test_twttr |
| 6 | File I/O (CSV, images) | lines, pizza, scourgify, shirt |
| 7 | Regular expressions | numb3rs, response, um, watch, working |
| 8 | Object-oriented programming | jar, seasons, shirtificate |

A few worth a look:

- **shirt** (Set 6): overlays an image onto a photo using Pillow.
- **working** (Set 7): converts 12-hour work schedules to 24-hour time with regular expressions, with tests.
- **shirtificate** (Set 8): generates a PDF certificate with fpdf2.

## Running

Each problem lives in its own folder and runs on its own:

```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install pytest pillow fpdf2 inflect emoji pyfiglet requests tabulate validators
python Problem_Set_0/tip/tip.py
pytest Problem_Set_5
```
