Code Formatting & Style Guides
ESLint and Prettier

Naming Variables & Functions
Clarity Over Brevity, Avoid Abbreviations (Unless Universal), Avoid Generic Names
Classes → PascalCase
Functions → snake_case → get_user() NOT user()
Unchanging Values → UPPER_SNAKE_CASE

Writing Small, Focused Functions
learn how to write functions that do exactly one thing, clearly and simply

Avoiding Code Duplication
Don't Repeat Yourself (DRY)
repeated logic → put it in one function
use variables instead of repeating values
copy-paste the same block for multiple items (>2) → loop

Refactoring Code for Simplicity
refactor = improve readability and structure of code without changing how it works
Red, Green, Refactor
Abstraction
Composing - Extract, Inline
Moving Features Between Objects
Simplifying

Commenting & Documentation
When should you add comments? explain why, not what. When the intent or rationale is not obvious from the code. When documenting public APIs or interfaces. When assumptions, side-effects, or workarounds need to be communicated.
When should you avoid comments and instead improve the code? Redundant, Outdated. If the process is simple/obvious (not complex logic or algorithms). If the code can be made clearer through renaming functions/variables or breaking down complex logic.

Handling Errors & Edge Cases
Invalid Inputs, Guard Clauses, Exceptions

Writing Unit Tests for Clean Code
check whether a specific part (unit) of your program works correctly
PyTest, unittest (built-in), Nose