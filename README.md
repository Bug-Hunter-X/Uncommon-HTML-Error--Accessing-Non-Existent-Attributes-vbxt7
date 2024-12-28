# Uncommon HTML Error: Accessing Non-Existent Attributes

This repository demonstrates a subtle yet potentially problematic error in HTML: attempting to access a non-existent attribute on an HTML element.  While this might not always throw an explicit error, it can lead to unexpected behavior and make debugging challenging.

The `bug.html` file shows the problematic code, where we try to access a non-existent attribute.  The `bugSolution.html` file provides a corrected version that addresses the issue.

This type of error is particularly common when dealing with dynamically generated content or when integrating with third-party libraries that might not guarantee the existence of specific attributes.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the behavior in your browser's console (usually accessed by pressing F12). You will see 'undefined', which may be misinterpreted as the code working correctly when actually it may lead to unexpected results and bugs in the future.
4. Open `bugSolution.html` and compare the difference.