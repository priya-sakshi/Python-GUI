
**Python GUI application built using the Tkinter library.** 

It serves the following purposes:

1. **User Input:** The GUI allows the user to input three pieces of information:
  The parent folder for pictures (Pic).
  The parent folder for descriptions (Desc).
  A selected date (e.g., "2022-03-16").
2. **Folder Navigation:** Once the user provides the input, the code constructs folder paths based on this input.
  It constructs paths to the specified date folders within the Pic and Desc parent folders. 

3. **File Display:** The code then displays images and descriptions from the specified date folders within the GUI. It reads image files from the Pic date folder and corresponding description files from the Desc date folder and displays them side by side.
   
5. **Error Handling:** It includes basic error handling to check if the specified folders or files exist and provides a message in case of any issues.

The display will look as below:
![image](https://github.com/priya-sakshi/Python-GUI/assets/32618227/819e4ba5-6397-47df-91fb-e5a4194e845e)

  
Here are some common use cases for Tkinter GUI applications like the one I've developed:

1. **File Management Tool:** You can use Tkinter to build a file manager that allows users to browse, copy, move, and organize files and folders on their computer.

2. **Image Viewer:**  Create an image viewer that enables users to open, view, and navigate through images stored in specific folders.
   You can also add functionality for basic image editing.
   
4. **Data Visualization Tool:** If you have data in a specific directory structure, you can use this GUI to display data files (e.g., CSV, Excel) and their corresponding visualizations.
