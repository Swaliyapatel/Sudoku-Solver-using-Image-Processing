# Sudoku-Solver-using-Image-Processing
Problem Statement : Sudoku Puzzle Solver uses Image processing to solve the sudoku in python language. It uses backtracking algorithm. Backtracking algorithm is simply revert back to the previous step or solution as soon as we determine that our current solution cannot be continued into a complete one. We will use this principle of backtracking to implement our project. It finds the digits for each boxes in solver function and then overlay it to the original image

The proposed system of “Sudoku Solver Using Image Processing mainly includes the six steps.

Preprocessing Image
In this step we had converted our image into grey scale image, and also applied some thresholding and blur concepts on that image. Thresholding is a type of image segmentation where we can change the pixels of image to make the make easier to analyze. In thresholding we convert grey scale image to binary image that is ‘0’ for black color and ‘1’ for white color.

2.Find Contours
In this step we find Contours. Contours are nothing but curve joining all the continuous points along the boundary having same color intensity. Contours are useful for shape analysis, object detection and recognition. Border in blue color represent contour.

Classify Digit
In this step we are predicting the each digit from each box of the Sudoku.

Find Sudoku
In this step we are cropping the image to capture only Sudoku puzzle matrix

Find Solution
In this step it finds the Solutions to the blank places by using backtracking algorithm. The board of digits and blank places is passed to the SudokuSolver.py file and here it finds the answer for blank places.

Overlay Solution
At the end we just overlay our solution on our original image.
