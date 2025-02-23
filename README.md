# Uncommon HTML Bug: Incorrect getElementById Usage

This repository demonstrates a common, yet easily missed, error in HTML when using the `getElementById` method to access elements. The bug arises from including the '#' symbol, which is unnecessary and causes the method to fail.

## Bug Description
The `bug.html` file contains an incorrect usage of `getElementById`. The '#' symbol is included before the id, preventing the correct selection of the div element.  This results in the innerHTML not being updated.

## Solution
The `bugSolution.html` file provides the corrected code. The '#' symbol is removed from the getElementById() method, allowing the code to run correctly. 

## How to reproduce the bug
1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe that the text within the div does not change.

## How to fix the bug
1. Open `bugSolution.html` in a web browser.
2. Observe that the text within the div is successfully updated.