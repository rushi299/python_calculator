# A GUI Based Basic Calculator Using Python
## This Basic Project is assigned as classed work.

< This assignemt was completed using various basic GUI features of Python. This model is perfect for understanding how the < basic GUI features work in Python.

## Steps to create the calculator

## Step-1:

Create test.py, import sys package. Now import QApplication, QLabel and Qwidget into test.py from PyQt5.QtWidgets.

	- Now, make an application using QApplication()
	- Using QWidget() give the dimensions of the window as per required.
	- Print a hello message (This is just for checking) and then end the window using show().

## Step-2:

Create view.py, import Ot, QMainWindow, QLineEdit, QGridLayout, QPushButton, QVBoxLayout and Qwidget into test.py from PyQt5.QtWidgets.

	- Now, construct class GUI which calls constructor of QMainWindow.
	- Using different widget and layout functions, define the calculator's look and layout as needed.
	- Create a display bar at top for showing the entered digits in a calculator.
	- Now using tuples, define position of each and every button in the calculator layout.
	- Construct the grid layout of buttons perfectly.

## Step-3:
Create main.py and import sys package.

	- Define the main function.
	- Create and call an instance of QApplication.
	- Show the GUI using GUI() and show() methods.

## Step-4:
Create model.py and add the following in the module.

	- Define evaluateExpression method in it.
	- Pass the expression in the above listed method and check whether it throws any exception or not, if not then print the result.

## Step-5:
Create controller.py. In this module add the folloeing things:

	- Define a class named Controller.
	- Build a constructor which calls model and view parameters in it.
	- Define 3 functions in it:
		1. calculateResult: for evaluating result of expression.
		2. buildExpression: for validating and building the expression.
		3. connectSignals: to connect the expression through the buttons we defined in Step-3.


 