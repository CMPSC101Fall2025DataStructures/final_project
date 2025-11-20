# Testing Documentation

Name: Add Your Name Here
Group Name: Add Your Name Here
Date: Add Date Here

## Project Testing Overview

This document describes how you tested your application to ensure it works correctly and doesn't crash. Since we are not using automated testing frameworks like pytest, you should focus on manual testing strategies and user-level validation. If the type of test in the question does not apply to your application, you can skip it by writing "Not Applicable".

---

## 1. Basic Functionality Testing

### Does your application run without crashing?

TODO: Describe how you verified that your application starts and runs without errors. What happens when you run `python main.py`?

### What is your testing process?

TODO: Explain the steps you take each time you test your application. Do you have a routine or checklist you follow?

---

## 2. Feature Testing

### What are the main features of your application?

TODO: List the 3-5 core features or functions of your application.

Example:
1. Feature 1: [Description]
2. Feature 2: [Description]
3. Feature 3: [Description]

### How did you test each feature?

**Feature 1 Testing:**

TODO: Describe how you tested this feature. What inputs did you try? What outputs did you expect? What actually happened?

**Feature 2 Testing:**

TODO: Describe how you tested this feature. What inputs did you try? What outputs did you expect? What actually happened?

**Feature 3 Testing:**

TODO: Describe how you tested this feature. What inputs did you try? What outputs did you expect? What actually happened?

---

## 3. Input Validation Testing

### What types of user input does your application accept?

TODO: Describe the different types of input your program expects (e.g., text, numbers, file names, menu choices, etc.)

### How did you test with different inputs?

**Valid Input Testing:**

TODO: Describe what "valid" or "correct" inputs you tested with. Give specific examples of inputs you tried and what happened.

**Invalid Input Testing:**

TODO: Describe what "invalid" or "incorrect" inputs you tested with. What happens if the user types something unexpected? Give specific examples.

Examples to consider:

- Empty input (just pressing Enter)
- Wrong data type (text when expecting a number)
- Out-of-range values (negative numbers when expecting positive)
- Very long inputs
- Special characters

---

## 4. Edge Cases and Boundary Testing

### What edge cases did you consider?

TODO: Edge cases are unusual or extreme situations that might cause problems. Describe 2-3 edge cases you thought about for your application.

Examples:

- What if an input file is empty?
- What if a list has only one item (when there should be many)?
- What if the user enters the maximum/minimum possible value?

### How did you test these edge cases?

**Edge Case 1:**

TODO: Describe the edge case and what happened when you tested it. Did your program handle it correctly?

**Edge Case 2:**

TODO: Describe the edge case and what happened when you tested it. Did your program handle it correctly?

**Edge Case 3 (optional):**

TODO: Describe the edge case and what happened when you tested it. Did your program handle it correctly?

---

## 5. Error Handling Testing

### What errors does your program handle with try-except blocks?

TODO: List the type(s) of errors your exception handling is designed to catch (e.g., FileNotFoundError, ValueError, IndexError, etc.)

### How did you test your error handling?

TODO: Describe how you intentionally caused errors to verify that your try-except blocks work correctly.

Examples:
- For FileNotFoundError: Did you try to open a file that doesn't exist?
- For ValueError: Did you try to convert invalid text to a number?
- For IndexError: Did you try to access a list element that doesn't exist?

**Error Test 1:**

TODO: Describe what error you tested and how you verified your exception handling works.

**Error Test 2 (if applicable):**

TODO: Describe what error you tested and how you verified your exception handling works.

---

## 6. File I/O Testing

### What file operations does your application perform?

TODO: Describe whether your program reads from files, writes to files, or both.

### How did you test file operations?

**Reading Files:**

TODO: If your program reads files, describe how you tested this. What test files did you create? What happened if the file was empty? What happened if the file didn't exist?

**Writing Files:**

TODO: If your program writes to files, describe how you tested this. Did you verify that the correct data was written? Did you check what happens if the file already exists?

---

## 7. Bug Discovery and Fixes

### What bugs (types of) or problems (types of) did you find during testing?

TODO: Describe 2-3 bugs or issues you discovered while testing your application.

**Bug 1:**

- **Description:** What was the bug?
- **How you found it:** What were you doing when you discovered it?
- **How you fixed it:** What changes did you make to fix the problem?
- **Verification:** How did you verify the fix worked?

**Bug 2:**

- **Description:** What was the bug?
- **How you found it:** What were you doing when you discovered it?
- **How you fixed it:** What changes did you make to fix the problem?
- **Verification:** How did you verify the fix worked?

**Bug 3 (optional):**

- **Description:** What was the bug?
- **How you found it:** What were you doing when you discovered it?
- **How you fixed it:** What changes did you make to fix the problem?
- **Verification:** How did you verify the fix worked?

---

(Did you remember to add your name and date at the top of this document?)
