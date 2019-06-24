# Nogrod
Nogrod GUI

Nogrod is a script that runs both in Python 2.7 and 3.x which uses the tk-interface of the current platform to enable quick and easy data processing and data manipulation. The script was designed to process and reshape data stored in text files (CSV or tabstopp separated) without the need to open them in statistical software packages. The program has a few easy to use routines which allow aggregation, combination, cross tabulation, and some basic analysis functions such as contingency analysis, for numerical and non-numerical data.

The program is based on the Angrist engine for content analysis data input and is specifically designed to read and process the data stored from Angrist. It may, however, be used for any kind of data which is stored in textfiles.

## How to use it: Quick Start
In order to use Nogrod, three files (Nogrod.py, n_codebook.ini, and n.settings.ini) need to be in the same directory on your computer.
- On Windows: Install Python 2.7 or 3.x and double-click on Nogrod.py to start the program.
- On Mac: Technically, the Tk-Interface should work on Mac but it was not tested. The best practice to get it to run on Mac is to install a Windows Emulator (e.g. Wine) and install Python for Windows to run it from within this emulator.
- On Linux: Again, an emulator for Windows programs is recommended.

When the window opens, there is only one button: It allows you to select the data manipulation/analysis function. As soon as you choose a function, Nogrod guides you through the entry of required parameters to run the function. All parameters are entered by means of drop down menues, lists, and checkboxes.

Please refer to the full documentation, Nogrod_1-1.pdf, for further information.


## Update Log
Recent updates:
- As of Version 1.0, Nogrod may be used in Python 3.x
- As of version 1.1, Nogrod may also be included as a module to any Python 2.7 or 3.x script. Upon inclusion, most of the functions of Nogrod may be called directly. The syntax is provided in the glossary in the appendix of the documentation.


Next updates:
- Nogrod is currently being updated to include functions for text analysis, automated annotation, and machine learning. While the functions for creating corpora and ML by Support Vector Machines are already operational, dictionary annotation, term mapping and Naive Bayes prediction will follow soon. 
