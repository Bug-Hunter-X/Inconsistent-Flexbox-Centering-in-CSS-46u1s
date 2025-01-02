# Inconsistent Flexbox Centering Bug

This repository demonstrates a bug related to inconsistent flexbox centering behavior in CSS across different browsers. The issue stems from the way browsers handle the combination of `display: flex`, `justify-content: center`, and `align-items: center` when the flex container's dimensions are explicitly set.

## Bug Description

The primary problem is that centering using flexbox might not work as expected if the parent element's height is explicitly defined. In some browsers, the content within the container may not perfectly align to the center, especially if the content itself doesn't occupy the entire height of the container. 

## Solution

The provided solution uses a combination of techniques that are more robust across various browser versions to resolve the inconsistency.  It ensures both horizontal and vertical alignment regardless of the content's height. 

## Setup

1. Clone the repository.
2. Open `bug.html` (provided in the solution) in your browser to see the inconsistent centering.
3. Open `bugSolution.html` to see the corrected centering using the solution.