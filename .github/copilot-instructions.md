# Copilot Instructions for LEET-CODES-ODD25

## Project Overview
This repository contains solutions to LeetCode problems, organized by week and difficulty (Easy/Medium). Each solution is implemented in Python, typically within a `Solution` class, following LeetCode's submission format.

## Key Patterns & Conventions
- **File Structure:** All code and documentation currently reside in the root directory. Solutions are documented in `README.md` using code blocks.
- **Solution Format:** Each problem solution is a method inside a `Solution` class. For list-based problems, type hints (e.g., `List[int]`) are used, and `from typing import List` is included as needed.
- **Organization:** Problems are grouped by week and difficulty in the `README.md`. Each week has an "Easy" and "Med" section.
- **Python Version:** Use Python 3 syntax and features.

## Developer Workflows
- **Adding Solutions:**
  1. Add new solutions as code blocks in `README.md` under the appropriate week and difficulty.
  2. Follow the existing class/method structure for consistency.
- **Testing:**
  - There is no automated test framework in this repo. Test solutions interactively (e.g., in LeetCode or a local Python shell).
- **Dependencies:**
  - Use only standard Python libraries and `typing`.

## Project-Specific Guidance for AI Agents
- **Do not introduce new files** unless explicitly requested. All solutions and documentation should remain in `README.md`.
- **Preserve the week/difficulty structure** when adding or updating solutions.
- **Follow the `Solution` class pattern** for all new problems.
- **No external dependencies** beyond Python standard library and `typing`.
- **Keep code blocks concise and idiomatic.**

## Example Pattern
```python
class Solution:
    def exampleMethod(self, arg: int) -> int:
        # ...implementation...
        return result
```

Refer to `README.md` for more examples and the current structure.
