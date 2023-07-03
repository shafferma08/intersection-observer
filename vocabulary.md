1. **DOM (Document Object Model):** The programming interface for HTML and XML documents. It represents the structure of a document as a tree of objects.

2. **JavaScript:** A high-level, interpreted programming language that conforms to the ECMAScript specification. JavaScript is used primarily for enhancing web pages to provide for a more user-friendly experience.

3. **Intersection Observer API:** An API that provides methods to asynchronously observe changes in the intersection of a target element with an ancestor element or with a top-level document's viewport.

4. **Viewport:** The user's visible area of a web page. It varies with the device used to access the site, and could be smaller on a mobile phone than on a computer monitor.

5. **Callback:** A function that is to be executed after another function has finished executing. In this context, the callback function is invoked when the target element meets the specified visibility threshold.

6. **Target Element:** The DOM element that you want to detect whether it's in the viewport.

7. **Root Element:** The element that the target is intersecting. A null root element defaults to the browser viewport.

8. **Threshold:** A number or an array of numbers which indicate at what percentage of the target's visibility the observer's callback should be executed.

9. **Root Margin:** Margins that can be set on the root (or viewport) for calculating intersections, effectively allowing you to either grow or shrink each side of the root bounds rectangle. 

10. **Asynchronous:** The concept of performing operations concurrently, meaning multiple operations can be executed in a non-blocking manner. This term is used to describe how the Intersection Observer API works.

11. **Observe:** The action of instructing the Intersection Observer to start observing a specified DOM element.

12. **Unobserve:** The action of instructing the Intersection Observer to stop observing a specified DOM element.

13. **Bounding Box:** The smallest rectangular box which contains the entire element including its padding, margin and border.

14. **Intersection Root:** In the context of Intersection Observer API, the intersection root is the element relative to which the intersections are being calculated. This can be a specific ancestor element of the target or, when null, defaults to the top-level document's viewport.

15. **Intersection Ratio:** It's a property of the IntersectionObserverEntry object and is the ratio of the intersectionRect area to the boundingClientRect area. It's a decimal number between 0.0 and 1.0, where 0.0 means the target element is not intersecting the root, and 1.0 means the target element is completely within the root. The intersection ratio is used in conjunction with the thresholds to trigger the observer's callback function.
