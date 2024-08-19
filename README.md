# Curvetopia - A Journey into the World of Curves

**Team Name:** Pi-Thons  
**College Name:** IIT Roorkee  
**Team Members:** Md Atif Husain, Utkarsh Raj  

## Project Title
**Curvetopia - A Journey into the World of Curves**

## Problem Statement
This project aims to identify, regularize, and beautify various types of curves in 2D Euclidean space. The focus is on closed curves, particularly in symmetry and curve completion techniques. The project is divided into the following key tasks:

### Regularize Curves
- **Straight Lines:** Detect and regularize straight lines.
- **Circles and Ellipses:** Identify curves that represent circles or ellipses based on properties like equidistance from a center or having two focal points.
- **Rectangles and Rounded Rectangles:** Distinguish between rectangles and those with curved edges.
- **Regular Polygons:** Identify polygons with equal sides and angles.
- **Star Shapes:** Identify star shapes by looking for central points with multiple radial arms.

### Exploring Symmetry in Curves
- **Symmetry Detection:** Identify reflection symmetries in closed shapes, detecting lines of symmetry where the shape can be divided into mirrored halves.

### Completing Incomplete Curves
- **Curve Completion:** Address curves that have been "planarized," leading to gaps or partial holes, and complete these curves in a natural and aesthetically pleasing way.

## Approach and Methodology

### 1. Corner Detection Using Curvature
The first step in our process was to detect the corners of shapes using curvature analysis. This allowed us to accurately identify key points in the shape where changes in direction occur.

### 2. Fitting Regression Lines
For the detected corners, we applied a best-fit regression line to create straight lines wherever possible. This helped in simplifying the shapes and ensuring that they align with geometric primitives.

### 3. Merging Points to Create Closed Shapes
Based on the proximity of the points, we merged them to form closed shapes. This step was crucial in defining distinct boundaries and ensuring that all shapes are properly closed.

### 4. Shape Identification and Regularization
Once the closed shapes were formed, we identified each shape as a circle, square, rectangle, star, etc. Regularization was then applied to make each shape conform to its ideal geometric form.

### 5. Symmetry Detection
We explored reflection symmetry within the identified shapes, ensuring that the shapes are mirrored correctly across their axes of symmetry.

### 6. Curve Completion
For any shapes that had gaps or were incomplete, we applied curve completion techniques to fill in the missing sections, resulting in smooth and continuous shapes.

## Usage Instructions

### Input Format
The input consists of CSV files containing polylines that represent various shapes.

### Running the Code
1. Load the input CSV file using the provided reading functions.
2. Apply the regularization and symmetry detection algorithms to the loaded shapes.
3. If applicable, run the curve completion algorithm to fill in any gaps.

### Output
The output will be a set of regularized and completed curves, which can be visualized or saved as image or CSV files for further use.

Here is a glimpse of our project: 
![image](https://github.com/user-attachments/assets/d94489b6-08ee-4d61-bc31-9beb9cd88b4a)
![image](https://github.com/user-attachments/assets/e8871559-02af-44f5-b0da-17ba3199abea)
![image](https://github.com/user-attachments/assets/1fe06fee-47c0-4b35-a702-e7ff28d7e413)



## Demo
Check out our [Project Demo Video](https://drive.google.com/file/d/1mqFf9THEJBDAXzeijk4nDfnyTXPX-pID/).
