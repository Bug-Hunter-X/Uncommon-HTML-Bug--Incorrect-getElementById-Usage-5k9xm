# Uncommon HTML Bug: Incorrect getElementById Usage

This repository demonstrates a common yet easily missed mistake when working with `document.getElementById()` in HTML and JavaScript. The bug lies in how the element's ID is passed to the function.

## Bug Description
The provided HTML code attempts to hide a div element using JavaScript. However, the `getElementById()` function is called incorrectly.  The '#' symbol before the ID is incorrect and causes the element to not be found, leading to unexpected behavior.

## Solution
The solution involves correcting the way `getElementById()` is used. The '#' should not be passed into the method.  The corrected code will then successfully hide the div element.