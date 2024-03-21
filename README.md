# Trieur\_de\_Fichiers: A Step-by-Step Guide for Your Python Script (IPYNB Compatible)

This program is designed to help you efficiently manage and sort your files based on their extensions in the current working directory. In this guide, we'll walk you through each step of using Trieur\_de\_fichiers with various IDEs, including Jupyter Notebook and Visual Studio Code (VSC).

## Prerequisites

Before diving into the instructions, please ensure that you have the following tools installed:
**Keep in mind that `ipynb` files are Jupyter Notebook-specific and cannot be run directly using other IDEs or Python interpreters like VSC. However, you can save the contents of your script as a separate `.py` file to make it executable within any Python IDE or interpreter.**

**Before running the script, make sure that the script file (Trieur\_de\_fichiers.py) is placed inside the directory containing the files you wish to sort. The script does not require an explicit path variable since it sorts the files based on the current working directory.**  

- **Python**: An open-source programming language for developing a wide range of applications. You can download Python from their official website - <https://www.python.org/downloads/>. Make sure to install the latest version, along with the PIP package manager.
- [Visual Studio Code](https://code.visualstudio.com/Download): A free and open-source source code editor developed by Microsoft for Windows, Linux, and macOS.
- (Optional) Jupyter Notebook: An open-source web application for creating and sharing documents that contain live code, equations, visualizations, and narrative text. If you prefer using Jupyter Notebook, make sure to have it installed as well - <https://jupyter.org/install>.

## Getting Started with Visual Studio Code

1. **Install Python extension**: Open VSC and go to the Extensions tab (press 'Ctrl+Shift+X'). Search for 'Python' and install the official Microsoft 'Python: Python extension for Visual Studio Code'. This extension will provide syntax highlighting, IntelliSense (code completions), debugging support, and more.
2. **Open your script**: In VSC, open the `Trieur_de_fichiers.py` file by going to 'File' > 'Open Folder' or using the shortcut 'Ctrl+Shift+P'. Select the directory containing `Trieur_de_fichiers.py`, then click 'Open'.
3. **Run the script**: Press 'F5' (or click on the 'Run' button in the toolbar) to run the script. The script will start executing, and you can observe its progress within the Output window (View > Output). Once finished, you should see a confirmation message indicating that your files have been sorted into their respective folders based on their extensions.

## Using Trieur\_de\_fichiers with Jupyter Notebook

1. **Save your script as an .ipynb file**: You can save the code as an `.ipynb` file by going to 'File' > 'Save As' and providing a name for your notebook. Make sure the file is saved inside the directory containing the files you wish to sort.
2. **Open your script**: In Jupyter Notebook, open the `Trieur_de_fichiers.ipynb` file by navigating to the 'Trieur\_de\_fichiers' folder in the File Browser, and double-clicking on the file.
3. **Run your script**: In a new cell, paste the following line and run the cell by pressing 'Shift+Enter': `%run Trieur_de_fichiers.py`. The script will start executing, and you can observe its progress within the Output section (you can find it in the right sidebar). Once finished, you should see a confirmation message indicating that your files have been sorted into their respective folders based on their extensions.
