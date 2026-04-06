Digital Coordinate System
Note: The system is currently available only in Croatian language.

Overview
This project is a fully accessible web-based coordinate system and graph editor, designed to support both visual and non-visual users, including those using assistive technologies such as screen readers.

The system enables users to create, explore, and export mathematical graphs in a structured and accessible way.

It exists in two main versions:

- Basic version – focused on point-based graphing (primary school level)
- Advanced version – includes function plotting and expression building (secondary school level)

Key Features
1. Coordinate System Configuration
- Define custom ranges for:
  - X-axis (min/max)
  - Y-axis (min/max)
- Automatic validation of input ranges

2. Point Input and Visualization
- Add points by entering coordinates `(x, y)`
- Display all entered points in a structured list
- Automatically update the graph after the first rendering
- Optional feature:
  - Connect points with lines (in input order)

3. Graph Rendering
- Dynamic SVG-based graph generation
- Includes:
  - Axes (X and Y)
  - Grid lines
  - Axis labels and numeric markings
- Real-time updates without full redraw after initial rendering

4. Accessibility (Core Feature)

The system is designed with accessibility as a primary goal:

- Semantic HTML structure
- ARIA roles and live regions
- SVG with:
  - `<title>` and `<desc>` elements for screen readers
- Textual descriptions of:
  - Axis ranges
  - Points and their positions (including quadrants)
  - Graph structure

This makes the graph understandable even without visual perception.

5. Automatic Graph Description

After rendering, the system generates a detailed textual analysis including:

- Coordinate system range
- List of points with coordinates
- Quadrant classification of each point
- Minimum and maximum values (x and y)
- Information about point connections

6. Export Options

Users can export their work in multiple formats:

- PDF export
  - Uses browser print dialog ("Save as PDF")
  - Includes graph and full description

- Word document (.doc)
  - Contains:
    - Graph image
    - Textual analysis
- PNG image
  - Export of the graph as an image file

Advanced Version Features (Functions)

Available in the advanced file:  
📄 :contentReference[oaicite:0]{index=0}

7. Function Builder (Accessible Expression Editor)

- Build mathematical expressions step-by-step using:
  - Variables (x)
  - Numbers
  - Operators (+, −, ×, ÷, powers)
  - Functions (sin, cos, log, exp, sqrt, abs, etc.)
- No need for manual typing of complex expressions
- Fully accessible via keyboard

8. Function Plotting

- Plot multiple functions simultaneously
- Supports common mathematical expressions:
  - Polynomial functions
  - Trigonometric functions
  - Exponential and logarithmic functions
  - Absolute value and rational functions

9. Function Analysis

Automatically generated descriptions include:

- Verbal description of the function
- Approximate zeros (roots)
- Intersection with Y-axis
- Monotonicity (increasing/decreasing behavior)
- Special properties:
  - Asymptotes
  - Domain limitations
  - Discontinuities

Basic Version (Points Only)

Available in:  
📄 :contentReference[oaicite:1]{index=1}

- Focused on:
  - Learning coordinate systems
  - Plotting points
- Does not include functions
- Suitable for:
  - Primary education
  - Introductory mathematics

Target Users

- Students (primary and secondary school)
- Teachers (especially in inclusive education)
- Blind and visually impaired users
- Accessibility researchers and developers

Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript (no external libraries)
- SVG for rendering graphs

Accessibility Philosophy

This project is built on the principle that:

> Mathematics must be accessible to everyone, regardless of visual ability.

Instead of relying solely on visual output, the system provides:
- Structured interaction
- Textual equivalents of graphical content
- Keyboard-first usability

How to use?
1. Create a folder named "Koordinatni sustav".
2. Place the file index.html inside that folder.
3. Save the files koors.html and koors-fun.html into a subfolder named files within the Koordinatni sustav folder.

In future versions, this structure will be further simplified and improved.
