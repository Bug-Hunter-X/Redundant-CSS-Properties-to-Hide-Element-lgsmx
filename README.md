# Redundant CSS Properties to Hide an HTML Element
This example demonstrates a subtle bug in HTML that arises from misunderstanding the behavior of `display` and `visibility` properties in CSS.

The goal is to hide a div element. However, the code incorrectly uses both `display: none` and `visibility: hidden`, leading to unnecessary redundancy.  The `display: none` property is sufficient.

## Bug
The provided `bug.html` file contains the erroneous code.  It attempts to hide the div with both properties, causing the element to be hidden but not in an efficient way.

## Solution
The `bugSolution.html` file provides a corrected version using only the `display: none` property to achieve the desired effect efficiently.