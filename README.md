# PRODIGY_AD_01
# Introduction :
Python offers multiple options for developing a GUI (Graphical User Interface). Out of all the GUI methods, Tkinter is the most commonly used method. It is a standard Python interface to the Tk GUI toolkit shipped with Python. Python with Tkinter outputs the fastest and easiest way to create GUI applications. Creating a GUI using Tkinter is an easy task.
To create a Tkinter:
1. Importing the module – tkinter
2. Create the main window (container)
3. Add any number of widgets to the main window
4. Apply the event Trigger on the widgets.
# Code Explanation :
A. Using Python:
1. The code starts by importing the necessary modules.
2. The tkinter module provides all the basic functionality for creating graphical user interfaces.
3. We also create two functions to update and evaluate the expression.
4. Finally, we write driver code to initialize and manage our GUI window.
5. The code creates a simple calculator using the Tkinter module.
6. First, the code imports everything from the Tkinter module.
7. The equal() function is used to evaluate the final expression.
8. The clear() function is used to clear the contents of the text entry box.
9. Next, the driver code is created.
10. The geometry() method is used to set the size of the GUI window .
11. The code starts with a few basic objects: a Button object, which has properties for text, font, background color, and command; and a grid object.
12. The first three buttons (button1 through button3) each have their own individual commands associated with them.When the user clicks on one of these buttons, the corresponding command is executed.
13. For example, when the user clicks on button1, its command is to press the number 1 key.
14. Similarly, when the user clicks on button2’s command, it will be to press the number 2 key; and so on.
15. When the user clicks on button4’s command (to increase the value by 1), its grid row and column values will be set to 3 and 0 respectively.
16. And finally when clicking on button5’s command (to decrease the value by 1), its grid row and column values will be set to 2 and 1 respectively.
17. The code creates seven buttons, each with its own function.
18. When the user presses one of the buttons, the corresponding command is executed.
19. The first button, button1, has the function press(1).
20. When clicked, this button will execute the code lambda: press(1).
21. The second button, button2, has the function press(2), and so on.
22. When all seven buttons have been clicked, their functions will be executed in order.
B. Using android development:
1.Create a new project and name it Calculator.
2 Open res -> layout -> activity_main.xml (or) main.xml. Here we are going to create the application interface like add layouts, Button , TextView and EditText.
3 – Create a Linearlayout vertical, add a textview followed by two textfields Number(decimal) for writing numbers in it. Starting code of activity_main.xml
4. The interface part of the application is over, let’s focus on adding functionality to the application. This calculator app basically perform five operations i.e addition, subtraction, multiplication, division and reset. So for that we need to define these operation over button click. For that we use setOnClickListener() function.

parseDouble() is used to convert String value to double. By default the value is String and we need to convert it into Double to perform operation over it.
# Conclusion :
The Calculator App looks like this -
    ![Screenshot (9176)](https://github.com/RANJANA20-eng/PRODIGY_AD_01/assets/133365717/c9e9913a-b43b-4f23-b82c-aed0bd52eda8)
    ![image](https://github.com/RANJANA20-eng/PRODIGY_AD_01/assets/133365717/d18fd25f-d886-4447-bfbc-16dc0dd17fc4)

