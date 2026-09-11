# CSC360 Reflection — 01/09/2026

This session started with our group project assignment, and we spent time breaking the problem statement into smaller parts before coding. We covered the math behind drawing triangles from equations, including linear equations and vectors, and learned that three equations form a valid triangle only if each pair has exactly one unique intersection. We also discussed handling different valid input formats for the same equation.

Next we looked at a project involving clicking to draw circles and connecting them with arrows. Mouse listeners capture the click position to place each circle. Deletion works by redrawing the shape in the background color instead of truly erasing it, and arrows are drawn by dragging from one circle to another. We also discussed using a stack to implement undo functionality.

We then connected this to binary trees, since a lot of the same click and connect logic applies. Printing a tree in ASCII is different since there is no real canvas, so it relies on nested loops and character grids to simulate shapes using text.
