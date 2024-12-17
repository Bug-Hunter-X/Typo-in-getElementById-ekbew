# Uncommon HTML Bug: Typo in getElementById

This repository demonstrates a subtle yet common bug in HTML/JavaScript code: a typo in the `getElementById` method.

The bug is present in `bug.html`.  The JavaScript attempts to access the element with an incorrect method name (`getElementByIdx`). This results in a runtime error, failing to modify the content of the div element.  The correct version is shown in `bugSolution.html`.