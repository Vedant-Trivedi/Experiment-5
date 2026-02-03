# Experiment-5

## LAB REPORT: STUDY OF PYTHON DICTIONARIES

**Student Name:** Vedant Trivedi

**PRN:** 25070123121

**Experiment No:** 5

---

### 1. AIM:

To explore the properties and functionality of Python dictionaries, including key-value pairing, mutability, handling duplicate keys, and utilizing methods such as `.get()`, `.pop()`, and `.values()` for data management and conditional logic.

---

### 2. THEORY:

A **Dictionary** in Python is an unordered (as of Python 3.7+, insertion-ordered), mutable collection of items. Unlike lists that use positional indexing, dictionaries use unique **keys** to store and retrieve **values**.

* **Key-Value Pairs:** Each entry is defined as `key: value`. Keys must be immutable (like strings or numbers) and unique.
* **Duplicate Keys:** If a key is assigned multiple times, the last assignment overwrites the previous ones.
* **Access & Methods:** Values are accessed using square brackets `[]` or the `.get()` method. The `.pop()` method removes a key-value pair, while `.values()` returns a view of all values in the dictionary.
* **Logic Operations:** Dictionaries are highly efficient for lookup operations, such as credential verification or retrieving specific records from a dataset.

---

### 3. LOGIC:

The implementation covers four core functional areas:

1. **Data Structure Definition:** Demonstrating the creation of a dictionary (car details) and observing how duplicate keys (e.g., "year") are handled by the interpreter.
2. **Dynamic Updates:** Adding new keys (e.g., "color") and updating existing values (e.g., product prices) to show mutability.
3. **Lookup & Security Sim:** Implementing a basic authentication check where user input is compared against stored dictionary keys and values.
4. **Data Extraction:** Utilizing the `max()` function with a dictionary to identify specific data points, such as the highest scorer in a marksheet.

---

### 4. ALGORITHM (User Authentication System):

**Step 1:** Start.

**Step 2:** Initialize a dictionary `users` with predefined username-password pairs.

**Step 3:** Take `user_name` and `pw` (password) as input from the user.

**Step 4:** Use the `.get()` method to retrieve the password associated with the entered `user_name`.

**Step 5:** Compare the retrieved password with the user-inputted `pw`.

**Step 6:** If they match, display "Access Granted"; otherwise, display "Wrong Password or Username".

**Step 7:** End.

---

### 5. CONCLUSION:

In this experiment, I successfully analyzed the behavior of Python dictionaries. I observed that dictionaries provide a more intuitive way to represent real-world objects (like students or products) compared to lists. The ability to quickly retrieve values using keys and the automatic handling of duplicate entries makes them essential for efficient data mapping. My implementation of the credential check and the "Topper" identification proves that dictionaries are a robust tool for conditional data processing.

================================================================================
