# Swapping Variable Data

A beginner Python script that swaps the values of two variables using a temporary variable, like swapping the drinks in two glasses with a third, empty glass.

## What it does

- **Inputs:** two values, `glass1` and `glass2`, typed at the prompt (read as text).
- **Logic:** the classic three-step swap:
  1. `temp = glass1` (pour glass 1 into the spare glass)
  2. `glass1 = glass2` (pour glass 2 into glass 1)
  3. `glass2 = temp` (pour the spare glass into glass 2)
- **Output:** prints the new contents of `glass1` and `glass2`, now exchanged.

Any text works as input, since values are kept as strings.

## Concepts practised

- Reading user input with `input()`
- Variables and reassignment
- Swapping values with a temporary variable
- Comments (`#`)
- Printing several values with `print()`

In Python the same swap can also be written in one line as `glass1, glass2 = glass2, glass1`; this script uses the explicit version to show each step.

## How to run

Requires Python 3:

```bash
python3 Swapping.py
```

## Example session

```text
glass1: milk
glass2: juice
glass1: juice
glass2: milk
```

## Files

| File | Description |
| --- | --- |
| `Swapping.py` | The swap script |
| `README.md` | This file |

A beginner Python exercise in variables and assignment.

## Author

Anshuman Tewary · [GitHub](https://github.com/anshumantewary-pm) · [LinkedIn](https://www.linkedin.com/in/tewary-anshuman/)
