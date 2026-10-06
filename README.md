# AI Tools Lab

A Python project for the Artificial Intelligence Tools and Applications Lab (AGCS-25308), containing sorting algorithms and utility functions.

## Description

This repository includes:
- `sorting.py`: bubble sort implementation
- `utils.py`: helper functions (palindrome check, word count, temperature conversion)
- `hello.py`: first test program

## Installation

1. Install Python 3 from https://www.python.org
2. Clone this repository:
```bash
git clone https://github.com/rashim2550893/ai-tools-lab.git
cd ai-tools-lab
```

## Usage

```python
from sorting import bubble_sort
from utils import is_palindrome, count_words, celsius_to_fahrenheit

print(bubble_sort([5, 2, 9, 1]))        # [1, 2, 5, 9]
print(is_palindrome("Madam"))           # True
print(count_words("AI tools are fun"))  # 4
print(celsius_to_fahrenheit(100))       # 212.0
```

## Contributors

- Rashim Rajput (B.Tech CSE, 3rd Semester, Section 2)

## License

This project is licensed under the MIT License.
