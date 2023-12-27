# Sudoku-Solver-Team16
An Open CV app to recognize and solve sudoku Grids.

**OpenCV Sudoku Solver**

**Overview**

This project is an OpenCV-based Sudoku solver that utilizes computer vision techniques to recognize and solve Sudoku puzzles from images. The solver employs various image processing and computer vision functions to preprocess the input image, extract the Sudoku grid, and solve the puzzle.

**Table of Contents**

1. Reading and Displaying Image
2. Creating Mask for Color Range
3. Ordering Corners Function
4. Euclidean Distance Function
5. Get Dimensions Function
6. Create Periodic Mask Function
7. Periodic Denoise Function
8. Image Inversion Check Function
9. Get All Contour Points Function
10. Get Image Intensity Function
11. Get Image Contrast Function
12. Basic Image Preprocessing and Initial Checks
13. Image Processing Conditions and Pipelining
14. Handling Low Contrast or Noisy Images
15. Final Image Processing and Perspective Transformation
16. Separate the Number Tiles
17. Preprocessing The Image for Template Matching
18. Reading Templates from Folder
19. Template Matching and its Helper Function
20. Solving the Sudoku

**Details**
1. Reading and Displaying Image
This section handles the loading and display of the input image.

2. Creating Mask for Color Range
Creates a mask for a specific color range in the input image to isolate the Sudoku grid.

3. Ordering Corners Function
Defines a function to order the corners of the Sudoku grid, essential for subsequent perspective transformation.

4. Euclidean Distance Function
Calculates the Euclidean distance between two points.

5. Get Dimensions Function
Retrieves the dimensions of the Sudoku grid.

6. Create Periodic Mask Function
Generates a periodic mask to remove unwanted grid lines or artifacts.

7. Periodic Denoise Function
Applies denoising techniques to the periodic mask.

8. Image Inversion Check Function
Checks if inverting the image improves the Sudoku grid detection.

9. Get All Contour Points Function
Finds and retrieves all contour points in the image.

10. Get Image Intensity Function
Calculates the intensity values of the pixels in the image.

11. Get Image Contrast Function
Evaluates the contrast of the input image.

12. Basic Image Preprocessing and Initial Checks
Performs basic preprocessing steps and checks on the input image.

13. Image Processing Conditions and Pipelining
Establishes conditions for different image processing scenarios and sets up the processing pipeline.

14. Handling Low Contrast or Noisy Images
Includes strategies to handle low-contrast or noisy images.

15. Final Image Processing and Perspective Transformation
Applies final image processing steps and performs perspective transformation to extract the Sudoku grid.

16. Separate the Number Tiles
Segments the Sudoku grid into individual number tiles.

17. Preprocessing The Image for Template Matching
Preprocesses the image for template matching to recognize numbers in the Sudoku grid.

18. Reading Templates from Folder
Reads template images from a specified folder for template matching.

19. Template Matching and its Helper Function
Implements template matching to recognize numbers in the Sudoku grid.

20. Solving the Sudoku
Utilizes a Sudoku-solving algorithm to solve the puzzle based on the recognized numbers.


**Usage**
Clone the repository.
Install the required dependencies.
Run the main script, providing the path to the Sudoku image.
Feel free to explore and adapt the code for your specific use case or contribute to the project's development.

**Acknowledgments**
Special thanks to the OpenCV community for their contributions and to Engineer Ahmed Salama for his invaluable guidance.
