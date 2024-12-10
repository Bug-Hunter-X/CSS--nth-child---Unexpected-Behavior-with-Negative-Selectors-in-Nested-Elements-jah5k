# CSS :nth-child() Unexpected Behavior with Negative Selectors in Nested Elements

This repository demonstrates an unusual CSS issue involving the unexpected behavior of the `:nth-child()` pseudo-class when used with negative selectors within nested elements.  The issue might manifest as inconsistent styling across different browsers.

## Description
The core problem lies in the way browsers interpret negative `:nth-child()` selectors in complex nested structures.  While generally functional, the results may not always be intuitive, particularly when dealing with varying levels of nesting.

## Bug Report
The `bug.css` file contains the problematic CSS code.  The `bugSolution.css` file provides an alternative approach to achieve the intended styling without relying on potentially unpredictable negative `:nth-child()` selectors in nested structures.

## Solution
The provided solution utilizes a more robust and predictable approach to target and style the intended elements.  This avoids the complexities and potential inconsistencies associated with negative `:nth-child()` selectors in nested contexts.