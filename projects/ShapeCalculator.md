---
layout: project
type: project
image: img/image.png
title: "BasicShapeCalculator"
date: 2022
published: true
labels:
  - Educational Technology
  - C++
  - Calculator
summary: "This C++ program is a shape calculator that allows users to calculate the area and volume of various geometric shapes, including circles, spheres, and cubes, using object-oriented principles."
---


This C++ code implements a simple geometric shape calculator using object-oriented programming (OOP) principles. The program defines a base class Shape, which serves as an abstract class for various specific shape types such as circles, spheres, cylinders, squares, cubes, triangles, and tetrahedrons. The base class includes several virtual methods, such as name(), inputData(), area(), and printDetails(), which are intended to be overridden by derived shape classes to calculate and display the area, surface area, and volume of specific shapes.

The code follows a modular structure, where each shape has its own class that inherits from the base class Shape. Each shape class is responsible for implementing specific calculations related to that shape. For example, a Circle class will calculate its area, while a Sphere class will calculate both surface area and volume. The user interacts with the program through a menu that allows them to select a shape and input necessary data, such as radius or side lengths. The program then performs the calculations and displays the results, including area and volume, where applicable.

The main() function drives the program by creating an array of shape objects and presenting the user with a menu to select a shape. The selected shape's data is gathered using the inputData() function, which prompts the user to enter relevant measurements (e.g., radius, height, side lengths), and the results are printed using printDetails(). The menu allows the user to repeatedly select shapes, perform calculations, and view results until they choose to quit the program. The code also includes constants like NUM for the number of shape options and MY_PI for calculating areas and volumes involving circles and spheres.

![Screenshot 2024-09-05 083800](https://github.com/user-attachments/assets/0d839513-7fc2-411f-b0d5-4c741cdb5822)










