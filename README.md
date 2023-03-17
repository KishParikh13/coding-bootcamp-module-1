# Code Refactor Starter Code
Module 1 Challenge from Berkeley's Coding Bootcamp Summer 2023

**Github Pages Link**: https://kishparikh13.github.io/coding-bootcamp-module-1/

## Overview
This exercise was to go over the basics of accessibility standards on the web and best practices when structuring html. To do this we refactored some starter code according the below acceptance criteria.

**User Story**:
```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

**Acceptance Criteria**:
```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

See `before.html` for the starter code that was given.

## What I did
I went line by line through the acceptance criteria, like a checklist, and made the appropriate changes. Half of the changes involved changing tags and attributes of html elements. The other half of the changes required updating the css file, renaming classes and changing a few selectors. Overall I removed a lot of duplative css classes and restructured one off class selectors into ids.

I also made one change not included in the acceptance criteria. I noticed one of the links in the navigation didn't work because the corresponding section (the link anchor) was missing an ID. I simply added the ID to the section to solve that problem.

## End Result
I created a `before.html` file to show the original html before my refactoring. This can be compared wiith `index.html` to see what changes I made. See the published url and image below.

**Github Pages Link**: https://kishparikh13.github.io/coding-bootcamp-module-1/

![Final webpage](site-screenshot.jpg)