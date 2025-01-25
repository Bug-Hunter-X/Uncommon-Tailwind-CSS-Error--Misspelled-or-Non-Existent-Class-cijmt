# Uncommon Tailwind CSS Error: Misspelled or Non-Existent Class

This repository demonstrates an uncommon error in Tailwind CSS that arises from using a utility class that doesn't exist or has a misspelling.  The error is subtle and may not always throw an immediate error message, making it difficult to debug.

The `bug.js` file contains the code with the error. The `bugSolution.js` file provides the corrected code.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js` and observe the incorrect Tailwind class usage.
3. Run the application and observe the unexpected behavior of not showing styling for the text.
4. Open `bugSolution.js` to see the corrected code.
5. Run the corrected code to see the intended outcome. 

## Solution

The solution involves carefully checking all Tailwind CSS classes for correct spelling and confirming their existence in your Tailwind configuration.