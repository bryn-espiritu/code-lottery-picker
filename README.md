# 🎰 Code Lottery Picker

A simple, dark-themed lottery picker that randomly selects one winning code from a list. The selected code is revealed with a scrambling animation followed by a character-by-character reveal.

## Features

- **Single-list entry:** Paste multiple codes into one text area, with one code per line.
- **Bulk paste support:** Easily copy and paste codes from Excel, Google Sheets, or a plain-text list.
- **Automatic code count:** Shows how many non-empty codes have been entered.
- **Collapsible entry panel:** Hide the code list while keeping the Draw Winner and Clear buttons visible.
- **Random winner selection:** Selects one entry at random from the submitted list.
- **Animated reveal:** Scrambles characters before revealing the winning code one character at a time.
- **Responsive layout:** Works on desktop and mobile screen sizes.
- **No installation required:** Runs directly in a modern web browser.

## How to Use

1. Open the [Code Lottery Picker](https://github.com/bryn-espiritu/code-lottery-picker).
2. Open `index.html` or download the file to your computer.
3. Open `index.html` in a modern browser such as Google Chrome, Microsoft Edge, or Firefox.
4. Paste your entries into the text area, placing **one code per line**.
5. Check the displayed code count.
6. Click **DRAW WINNER** to select and reveal a random winning code.
7. Click **CLEAR** to remove the entries and reset the result.

## Example Entries

Paste a list like this into the entry area:

```text
L60X
D5LV
3HPR
2Y6H
Q53T
KPTU
N6I9
SDJ9
L0UF
7FD5
```

Blank lines are ignored.

## Project Structure

```text
code-lottery-picker/
├── index.html   # Complete lottery picker application
└── README.md    # Project documentation
```

## Technology

- HTML
- CSS
- Vanilla JavaScript

The application runs entirely in the browser and does not require a server, database, or external JavaScript libraries.

## Fairness Note

The picker uses JavaScript's `Math.random()` to select an entry. It is intended for casual drawings and entertainment, not for regulated, high-stakes, or security-sensitive lotteries.

## License

No license has been specified for this project yet.
