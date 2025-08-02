Ideal function should be **small** and do **one thing**

### Arguments
- Minimize the number of arguments (never more than 3, optimally 1)
- Avoid output arguments (functions should not modify the input)
- Don't use flag (boolean) arguments

### Side Effects
- A function should not change the state of something outside of its scope unless it is function's clear purpose

### Other Principles
- Use exceptions rather than return codes
- Keep error handling seperate from core logic
- DRY (do not repeat yourself)
