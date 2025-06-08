# Sudoku Validator

## Description
A Python program that validates 9x9 Sudoku puzzles according to:
- Standard Sudoku rules (rows, columns, 3x3 boxes)
- Optional custom irregular regions

## Requirements
- Python 3.x

## Usage
1. Create your Sudoku board as a list of lists (9x9)
2. Optionally define custom regions as lists of (row, col) tuples
3. Call `validate_sudoku(board, custom_regions)`

## Input Formats
- Empty cells: `0` or `'.'`
- Filled cells: `1-9` (as integers or strings)

## Examples
See the test cases in the Python file for complete examples.

## License
MIT License - Free for educational use
