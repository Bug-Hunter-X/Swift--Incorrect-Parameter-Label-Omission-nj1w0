# Swift: Incorrect Parameter Label Omission

This repository demonstrates a common, yet subtle error in Swift: omitting parameter labels when calling a function that explicitly defines them.

**Bug:**
The `calculateArea` function requires labels `width:` and `height:`.  Omitting these leads to a compiler error.  The code in `bug.swift` shows the incorrect usage.

**Solution:**
The `bugSolution.swift` file shows the correct way to call the `calculateArea` function, including the necessary labels.

**Learning Points:**
* Swift emphasizes readability through explicit parameter labels.
* Forgetting parameter labels, even when seemingly obvious, will cause compile-time errors.
* Always check the function signature to ensure you are providing the correct arguments with their respective labels.