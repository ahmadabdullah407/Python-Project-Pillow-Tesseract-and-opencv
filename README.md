# Python-Project-Pillow-Tesseract-and-opencv
## Description:
- This is assignment and final course Project of course [Python Project, pillow,tesseract and opencv](https://www.coursera.org/learn/python-project) which is project course for [Python 3 Programming Specialization](https://www.coursera.org/specializations/python-3-programming) offered by [University of Michigan](https://umich.edu/) on [Coursera](https://www.coursera.org/).  
- There are two different [jupyter notebbok](https://jupyter.org/) files [Assignment 1](https://github.com/ahmadabdullah407/Python-Project-Pillow-Tesseract-and-opencv/blob/main/assignment_1.ipynb) file and [Final Project](https://github.com/ahmadabdullah407/Python-Project-Pillow-Tesseract-and-opencv/blob/main/Final%20project.ipynb) file for course assignment and final project respectively.
- There is a [readonly](https://github.com/ahmadabdullah407/Python-Project-Pillow-Tesseract-and-opencv/tree/main/readonly) directory which contains necessary files that are referred inside code.
- There is also an html file provided for assignment 1.
## Assignment:
  ### Requirements:
  - You need [Jupyter Notebook](https://jupyter.org/) or alternate for assigment.
  - Assignment requires pillow module installed to run the code.
  ### Working:
  - Assignment takes 1 gif image file and creates a contact sheet representing three different color intensities (10%, 50%, 90% of original) for red green and blue color channels respectively, making in total 9 different variants of original image.
  - Red is channel 0,Green is channel 1 and blue is channel 2.
## Final Project:
### Requirements:
- You need [Jupyter Notebook](https://jupyter.org/) or alternate for this project.
- This project requires following libraries installed in order to operate:
  - zipfile (Already builtin inside Python).
  - PIL/pillow library.
  - pytesseract library.
  - OpenCV library.
  - NumPy library.
- small-img.zip and images.zip files are not provided inside [readonly](https://github.com/ahmadabdullah407/Python-Project-Pillow-Tesseract-and-opencv/tree/main/readonly) directory due to their bigger size, so you need to provide them yourself.
### Working:
1. After execution of code system ask you to input 1 string you need to search for in datafiles(small_img.zip and images.zip in this case).
2. System extracts the png image files from zip files using zipfile module.
3. System then scans for words in the newspaper pages(png image files) provided inside zip files using pytesserect module.
4. System then checks if the string you provided is on the pages.
5. If string is on the page it will scan out all the pages and extract all faces using xml file provided in readonly directory as well as numpy and opencv libraries.
6. Finally a contact shhet is created for those faces which is displayed on terminal.
7. If there are no faces on the pages System will show a string 'But there were no faces in that file!'.
