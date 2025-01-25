# Tailwind CSS Gradient Rendering Issue

This repository demonstrates a potential issue with Tailwind CSS's gradient functionality. The issue may arise when using colors that are too similar or when encountering browser incompatibility with gradient directions.

## Bug Description
The `bg-gradient-to-r from-blue-500 to-purple-500` class generates a gradient that may not be visible or as expected depending on browser and color differences.

## Bug Solution
To fix the problem, ensure the `from` and `to` colors have a greater contrast. Also, consider providing fallback styles or a different gradient direction for better browser support.