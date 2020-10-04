# A GUI Based Basic Calculator Using Python
## This Basic Project was assigned as classed work from the professors.

> This assignemt was completed using various basic GUI features of Python. This model is perfect for understanding how the basic GUI features work in Python using PyQt5.QtWidgets.

## Steps to create the calculator

## Step-1:

Create test.py, import sys package. Now import QApplication, QLabel and Qwidget into test.py from PyQt5.QtWidgets.

	- Now, make an application using QApplication()
	- Give dimensions of the output window according to your choice by using QWidget().
	- Print a hello message (Checking for window whether it is working or not) and then end the window using show().

## Step-2:

Create view.py, import Ot, QMainWindow, QLineEdit, QGridLayout, QPushButton, QVBoxLayout and Qwidget into test.py from PyQt5.QtWidgets.

	- Now, create class GUI which calls constructor of QMainWindow.
	- Using different widget and layout functions, define the calculator's look and layout as needed.
	- Create a display bar at top for showing the entered digits in a calculator.
	- Now using tuples, define position of each and every button in the calculator layout.
	- Construct the grid layout of buttons perfectly.

## Step-3:
Create main.py.

	- Define the main function.
	- Create and call an instance of QApplication.
	- Show the GUI using GUI() and show() methods.

## Step-4:
Create model.py and add the following in the module.

	- Define evaluateExpression method in it.
	- Pass the expression in the above listed method and check whether it throws any exception or not, if not then print the result.

## Step-5:
Create controller.py. In this module add the following things:

	- Define a class named Controller.
	- Build a constructor which calls model and view parameters in it.
	- Define 3 functions in it:
		1. calculateResult: for evaluating result of expression.
		2. buildExpression: for validating and building the expression.
		3. connectSignals: to connect the expression through the buttons we defined in Step-3.

> **After following the above mentioned steps, open an Anaconda prompt and navigate to the location where you have stored the package of python_calc or if you're using only python then install PyQt5 using the command 'pip install pyqt5'.
> Now, try to run to the main.py file, it will show you a layout like a basic calculator and then by entering values you can do your calculations on your newly created basic calculator.** 
> ** After excecuting the file you will see the output on screen like this as below in the figure. 
![](main-py.png)

 